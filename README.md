# Software Templates

Collection of Software Templates / Golden Path for Backstage.


For now, the easiest way to use to WIP templates is to start from the RH-TAP demo available on Red Hat Demo System.

Once the demo is started, you can add them to the gitlab repository
`https://gitlab-gitlab.apps.xxxxxx/summit-lab/backstage-workshop/blob/master/showcase-templates.yaml` 

For example, last "target" line is the quarkus-rest-postgresql-template software template :

```yaml
apiVersion: backstage.io/v1alpha1
kind: Location
metadata:
  name: showcase-templates
  description: A collection of Backstage templates for RH Summit
spec:
  type: url
  targets:
    - https://gitlab-gitlab.apps.cluster-rbjvq.sandbox1340.opentlc.com/summit-lab/backstage-workshop/blob/master/scaffolder-templates/poi-backend/template.yaml
    - https://gitlab-gitlab.apps.cluster-rbjvq.sandbox1340.opentlc.com/summit-lab/backstage-workshop/blob/master/scaffolder-templates/poi-gateway/template.yaml
    - https://gitlab-gitlab.apps.cluster-rbjvq.sandbox1340.opentlc.com/summit-lab/backstage-workshop/blob/master/scaffolder-templates/poi-map/template.yaml
    - https://github.com/rh-trucathon/trusted-application-pipeline-templates/blob/main/scaffolder-templates/quarkus-rest-postgresql-template/template.yaml

```
