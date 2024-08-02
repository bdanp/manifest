## Issues in the Provided Manifest

The kind field should be Deployment instead of Deploy.

## Steps to Correct and Add Resource Limits and Requests

1. Correct the Kind
 - Change `kind: Deploy` to `kind: Deployment`
2. Add Resource Requests and Limits
 - Add the resources field under the container specification to define the resource requests and limits.

