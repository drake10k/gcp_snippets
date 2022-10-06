### Create a simple Compute Engine instance:

#### with default zone set

```bash
gcloud compute instances create <vm_name>
```

#### without default zone set OR in another zone than the default one

```bash
gcloud compute instances create <vm_name> --zone=<your_zone>
```