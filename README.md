# Torque Building-blocks Marketplace

Welcome to Torque's marketplace - The place to find, learn about and share IaC modules, container orchestration assets and Torque bluerpints for easy onboarding to Torque.

### Already have a Torque account? Jump to step X


## Step 1: Open Torque Portal
* In [Quali Torque page](https://www.qtorque.io/), click the __GET STARTED__ button.
![QTorque.io](pics/torque-intro.png)

## Step 2: Register to Torque
* You can register with your email, GitHub or Gitlab accounts. Already have an account? Just sign in.
![register](pics/register.png)

## Step 3: Create a new space and onboard the marketplace repository as an asset repository
1. Navigate to __Admin Console > Spaces__.
2. Click __Create Space__. 
3. Provide a space name (no spaces), select the space logo and color. 
4. Click __Create__.
![register](pics/new-space.png)
5. As this repository is hosted in GitHub, select the GitHub logo.
6. Provide https://github.com/QualiTorque/Torque-Blueprint-Marketplace as the repository URL and click __Connect__. GitHub authentication is done in the background. If you encounter any issues, take a look at our documentation page on GitHub authentication and follow the steps [here](https://docs.qtorque.io/admin-guide/source-control-github). 
7. Click __Discover Assets__.
  ![register](pics/repository-onboarding.png)
  
  Asset discovery scans the repository sources and finds all known and supported IaC assets and container orchestration code, and lists them in the discovery form. 
8. Select assets and let Torque generate blueprints out of them for you.
  ![register](pics/asset_discovery.png)

* Lastly, we need to choose the cloud that will be associated to the space from the existing list of clouds configured in your Torque account. if you don't have a cloud configured, follow the Torque documentation for more information [here](https://docs.qtorque.io/getting-started/Connect%20a%20Kubernetes%20Cluster).
  ![register](pics/connect_cloud.png)

## Step 4: Add a bluerpint repository
1. Navigate to the newly created space's __Settings > Repositories__ page. You can now see the marketplace repositiory configured as an asset repository. Next, let's add the repository as a blueprint repository to enjoy existing blueprints that use multiple building blocks and custom orchestration.
2. Click __Add a Repository__ under the blueprint Repos section. 
3. Select __GitHub__, paste https://github.com/QualiTorque/Torque-Blueprint-Marketplace, and click __Connect__.

## Step 5: Give it a try!
1. Navigate to the space's __Blueprints__ catalog to see all the blueprints that were imported from the blueprint repository.
2. Publish a blueprint(s) you would like to use and __Launch__ it.
   ![register](pics/publish.png)
