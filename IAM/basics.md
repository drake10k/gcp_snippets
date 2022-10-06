### Create a Service Account:

```bash
gcloud iam service-accounts create <service_account_name> --display-name "<service_account_display_name"
```

### Assign role to an existing Service Account:

> $GOOGLE_CLOUD_PROJECT environment variable should be already defined and it contains your project's ID

```bash
gcloud projects add-iam-policy-binding $GOOGLE_CLOUD_PROJECT --member serviceAccount:<your_service_account_name>@${GOOGLE_CLOUD_PROJECT}.iam.gserviceaccount.com --role <role_to_assign>
```