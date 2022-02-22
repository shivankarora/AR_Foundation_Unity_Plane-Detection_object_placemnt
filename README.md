# AR_Foundation_Unity_Plane-Detection_object_placemnt


https://user-images.githubusercontent.com/63502234/155088056-4536e068-f5d2-4de1-b806-69770157ff80.mp4



https://user-images.githubusercontent.com/63502234/155088350-e3c75702-62a8-476d-858a-bddb3b439d1a.mp4


Shivank Arora
RA1911003011013


This set of sample relies on two Unity packages:

Google ARCore XR Plug-in 



ARFoundation (https://docs.unity3d.com/Packages/com.unity.xr.arcore@5.0/manual/index.html)


ARSubsystems

ARFoundation is built on "subsystems" and depends on subsystems defined in UnityEngine.XR.ARSubsystems namespace. This namespace defines an interface, and the platform-specific implementations are in the Google ARCore and Apple ARKit packages. ARFoundation turns the AR data provided by ARSubsystems into Unity GameObjects and MonoBehavours.


PlaneClassification

This sample shows how to query for a plane's classification. Some devices attempt to classify planes into categories such as "door", "seat", "window", and "floor". This scene enables plane detection using the ARPlaneManager, and uses a prefab which includes a component which displays the plane's classification, or "none" if it cannot be classified.
