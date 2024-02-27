# Step 1

## Secrets

| key                    | value |
|------------------------|-------|
| OVH_APPLICATION_KEY    |       |
| OVH_APPLICATION_SECRET |       |
| OVH_CONSUMER_KEY       |       |

## Variables

| key              | value |
|------------------|-------|
| OVH_ENDPOINT     |       |
| OVH_FLAVOR_NAME  |       |
| OVH_PROJECT_ID   |       |
| OVH_PROJECT_NAME |       |
| OVH_REGION       |       |
| WITNESS_ID       |       |

# Step 2

Trigger bootstrap_servers

Copy kubeconfig from OVH 

| key                    | value |
|------------------------|-------|
| KUBE_CONFIG            |       |

# Step 3

Trigger bootstrap_witnesses

# Step 4

Copy witness signing key from "Generate Witness Key" (github action)

https://github.com/bitshares/dev.bitshares.works/blob/master/docs/bts_guide/tutorials/witness-change-key.rst
