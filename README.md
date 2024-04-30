This directory contains the VSAs for GKE VM images. The subfolder structure will follow the pattern -

```
<VM_IAMGE_PROJECT>/<VM_IMAGE_NAME>:<VM_IMAGE_ID>.intoto.jsonl
```

For eg: VSA for -
`gke-master-images:gke-1288-gke1166000-cos-109-17800-147-54-c-pre` will be stored at -
`gke-master-images/gke-1288-gke1166000-cos-109-17800-147-54-c-pre:7627254251642584359.intoto.jsonl`
where `7627254251642584359` is GCE VM image ID.

* GitHub repo: https://github.com/googlecloudPlatform/gke-vsa