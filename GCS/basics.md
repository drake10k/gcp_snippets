### Create a simple bucket:

```bash
gsutil mb gs://<bucket_name>
```

### Copy a file from GCS to Cloud Sheel

```bash
gsutil cp gs://<your_bucket_file_path> <your_file_name>
```

### Copy a file from Cloud Sheel to a GCS bucket
```bash
gsutil cp cat.jpg gs://<bucket_name>
```

### Copy a file from one GCS bucket to another GCS bucket
```bash
gsutil cp gs://<your_source_bucket_file_path> gs://<your_destination_bucket_file_path>
```
