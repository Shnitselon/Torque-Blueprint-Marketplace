# Torque Building-blocks Marketplace

Welcome to Torque's marketplace - The place to find, learn about and share IaC modules, container orchestration assets and Torque bluerpints to streamline your onboarding to Torque and learn about the latest cool features and functionality.

### Already have a Torque account? Jump to step X


## Step 1: Open Torque Portal
* On the [Quali Torque page](https://www.qtorque.io/), click the __GET STARTED__ button.
![QTorque.io](pics/torque-intro.png)

## Step 2: Register to Torque
* Registration to Torque can be done using email, GitHub or Gitlab accounts. Already have an account? Just sign in.
![register](pics/register.png)

## Step 3: Create a new space and onboard the marketplace repository as an asset repository
* Navigate to __Administration > Spaces__.
* Click __Create Space__. 
* Give the space a name, select the space logo and color. 
* Click __Create__.
![register](pics/new-space.png)

* As this repository is hosted on GitHub, select the GitHub logo, provide https://github.com/QualiTorque/Torque-Blueprint-Marketplace as the repository URL and click __Connect__. GitHub authenticaiton is done in the background. If you encounter any issues, visit our documentation page on GitHub authentication and follow the steps [here](https://docs.qtorque.io/admin-guide/source-control-github). Click __Discover Assets__.
  ![register](pics/repository-onboarding.png)

* Assets discovery scans the repository sources for all known and supported IaC assets and container orchestration code and shows them in the discovery form. You can now select assets and generate bluerpints out of them quickly and easly.
  ![register](pics/asset_discovery.png)

* Lastly, we need to choose the cloud that will be associated to the space from the existing list of clouds configured in your Torque account. if you don't have a cloud configured yet, follow Torque's docs for more information [here](https://docs.qtorque.io/getting-started/Connect%20a%20Kubernetes%20Cluster).
  ![register](pics/connect_cloud.png)

## Step 4: Add a bluerpint repository
* In the newly created space, click __Repositories__. You can now see the marketplace repository configured as an asset repository. Next, add the repository as a bluerpint repository to enjoy existing bluerpints that use multiple building blocks and custom orchestration.
* Click __Add a Repository__, choose __GitHub__ and paste "https://github.com/QualiTorque/Torque-Blueprint-Marketplace". 
* Click __Connect__.

## Step 5: Give it a try!
* Click __Bluerpints__ to see the catalog of the bluerpints that were inported from the blueprint repositories.
* Publish the bluprint you would like to use, and launch it.
   ![register](pics/publish.png)
