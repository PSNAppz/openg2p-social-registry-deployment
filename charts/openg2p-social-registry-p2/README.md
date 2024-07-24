# OpenG2P Social Registry Helm Chart - Part 2

As the maximum size of a helm chart cannot be more than 1MiB
(each etcd object can only hold maximum of 1MiB unless configured otherwise),
the OpenG2P Social Regsitry helm chart has been split into two parts.

This is the second part. This contains the following components:

- Superset
- eSignet

Skip this helm chart if you dont want to install these components.

## IMPORTANT

Whatever installation name chosen of Part 1, the same will have to be given for part 2 with suffix "-p2".

For example, if you want the installation name to be "sr", then the name for part 1 will have to be "sr", and the name for part 2 will have to be "sr-p2".
