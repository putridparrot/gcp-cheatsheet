# GCP (Google Cloud Platform) cheat sheet

A list of useful commands, params etc. for the GCP CLI

**General** 

| Command | Description |
|---------|-------------|
| gcloud version | Get the version |

**Current Configuration**

| Command | Description |
|---------|-------------|
| gcloud config list | Lists the active configuration |
| gcloud config list &lt;section&gt;| Lists the section in the active configuration |
|                             | Example: gcloud config list project |

**Artifact Registry**

| Command | Description |
|---------|-------------|
| gcloud artifacts repositories list --limit=5 | Lists the artifact registry upto a given limit |
| gcloud artifacts repositories list --filter=&lt;expression&gt; | Lists the artifact registry matching the expression |
