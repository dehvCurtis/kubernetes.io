# Configure a Pod to Use a PersistentVolume for Storage
This page shows you how to configure a Pod to use a PersistentVolumeClaim for storage. Here is a summary of the process:

- You, as cluster administrator, create a PersistentVolume backed by physical storage. You do not associate the volume with any Pod.
- You, now taking the role of a developer / cluster user, create a PersistentVolumeClaim that is automatically bound to a suitable PersistentVolume.
- You create a Pod that uses the above PersistentVolumeClaim for storage.


