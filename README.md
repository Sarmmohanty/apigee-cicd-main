# apigee-cicd-main# APIGEE-CICD
  A master repo for enabling CICD pipeline for below APIGEE components.

  * Proxies
  * Shared Flows
  * Integrations
  * Connectors
  * Target servers 
  * Products
  * KVM


  Each component has its own reusable workflow and can be used to enable CICD pipeline with few steps. 
  We also have created `Automatic repo creator workflow` which makes the reposotiry creation process facile.


## List of Reusable workflows
#### Automatic repo creator
> This workflow creates repository for given apigee component type along with all required configurations for CICD pipeline.

#### APIGEE Proxy
> This workflow deploys and undeploys the apigee proxies in to different environments of APIGEE in GCP.

#### APIGEE Shared Flows
> This workflow deploys and undeploys the apigee shared flows in to different environments of APIGEE in GCP.

#### APIGEE Integrations
> This workflow deploys and undeploys the apigee Integrations in to different environments of APIGEE in GCP.

#### APIGEE Connectors
> This workflow deploys and undeploys the apigee Connectors in to different environments of APIGEE in GCP.

#### APIGEE Target servers
> This workflow deploys and undeploys the apigee Target servers in to different environments of APIGEE in GCP.

#### APIGEE Products
> This workflow deploys and undeploys the apigee Products in to different environments of APIGEE in GCP.

#### APIGEE KVMS
> This workflow deploys and undeploys the apigee KVMS in to different environments of APIGEE in GCP.

## Getting Started

### Step 1:
* Create a new repository for apigee component using our reusable workflow: [Automatic Repo Creator](https://github.com/Sarmmohanty/apigee-cicd/actions/workflows/Repo-Creator.yml).

### Step 2:
* Go to newly created repository and make changes which are required to start with CICD flow.
