- # Setup Guide (Uploading to VRChat)

  ## 1. Preparation

  - Download and install Unity (2022.3.22f1)
  - Install VRChat Creator Companion (VCC)

  ![VCC0](../Manual_Pict/VCC0.png)

  ---

  ## 2. Required Packages

  Install the following packages via VCC:

  - Required Packages
    - lilToon → Add Repository from the official website
    - FaceEmo → Download via VCC
    - Modular Avatar → Download from the official website

  ---

  ## 3. Create a New Project

  Create a new project from "Create New Project".

  ![VCC1](../Manual_Pict/VCC1.png)

  Select "Unity 2022 Avatar Project", set any project name, and create the project.

  ![VCC2](../Manual_Pict/VCC2.png)

  ---

  ## 4. Install Required Packages

  After creating the project, select "Manage Project".

  ![VCC3](../Manual_Pict/VCC3.png)

  Install the following packages:
  
  - lilToon
  - Modular Avatar
  - FaceEmo
  
  If these packages are not displayed, repeat Step 2.
  
  Once lilToon, Modular Avatar, and FaceEmo are installed as shown below, setup is complete.
  
  ![VCC7](../Manual_Pict/VCC7.png)
  
  ---
  
  ## 5. Import Horoyoel
  
  - Select "Open Project" and open the project you created.
  
  ![OpenProject](../Manual_Pict/OpenProject.png)
  
  - In Unity, select **Assets → Import Package → Custom Package**.
  
  ![Unity1](../Manual_Pict/Unity1.png)
  
  - Select and import the distributed file: `HoroyoelVerXXX.unitypackage`  
    (`XXX` indicates the version number.)

  ![Unity2](../Manual_Pict/Unity2.png)

  After importing, the `Horoyoel` folder will be added to your Assets.

  ---
  
  ## 6. Place the Avatar in the Scene
  
  Drag and drop one of the following Prefabs into the Hierarchy:
  
  - `Assets/Horoyoel/Horoyoel_PresetA`  
    Horoyoel wearing the angel outfit

  - `Assets/Horoyoel/Horoyoel_PresetR`  
    Horoyoel wearing roomwear
  
  ![Unity3](../Manual_Pict/Unity3.png)
  
  If successful, Horoyoel will appear in the scene.
  
  ![Unity4](../Manual_Pict/Unity4.png)
  
  ---
  
  ## 7. Upload

  - From the Unity menu, open **VRChat SDK → Show Control Panel**.
  - Log in with your VRChat account.
  
  ![SDK1](../Manual_Pict/SDK1.png)
  
  After logging in, you can enter avatar information from the Builder tab.  
  Set the Name, Visibility, and thumbnail, then upload the avatar.
  
  > ⚠️ **Important**  
  > Visibility must be set to **Private**.  
  > Uploading this avatar as Public is a violation of the Terms of Use.
  
  ![SDK2](../Manual_Pict/SDK2.png)
  
  - Click **Build & Publish**.
  - Complete the upload.
  
  Done!
