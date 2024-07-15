This repository contains the VSAs (Verification summary attestations) for GKE VM
images. The subfolder structure follows the pattern -

```
<VM_IMAGE_PROJECT_ID>:<VM_IMAGE_PROJECT_NUMBER>/<VM_IMAGE_NAME>:<VM_IMAGE_ID>.intoto.jsonl
```

For eg: VSA for -
`gke-master-images/gke-1288-gke1166000-cos-109-17800-147-54-c-pre` is stored at -
`gke-master-images:78064567238/gke-1288-gke1166000-cos-109-17800-147-54-c-pre:7627254251642584359.intoto.jsonl`
where `78064567238` is the Project number & `7627254251642584359` is GCE VM image ID.