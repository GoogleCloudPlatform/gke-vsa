This directory contains the VSAs (Verification summary attestations) for GKE VM
images. (we are not making VSAs for container images public at the moment). The
subfolder structure will follow the pattern -

```
<VM_IMAGE_PROJECT_ID>:<VM_IMAGE_PROJECT_NUMBER>/<VM_IMAGE_NAME>:<VM_IMAGE_ID>.intoto.jsonl
```

For eg: VSA for -
`gke-master-images/gke-1288-gke1166000-cos-109-17800-147-54-c-pre` will be
stored at -
`gke-master-images:78064567238/gke-1288-gke1166000-cos-109-17800-147-54-c-pre:7627254251642584359.intoto.jsonl`
where `78064567238` is the Project number & `7627254251642584359` is GCE VM image ID.

* GitHub repo: https://github.com/googlecloudPlatform/gke-vsa

*Note:* This directory does **not** contain any source code. (proprietary or
otherwise)