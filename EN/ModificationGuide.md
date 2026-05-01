# Modification Guide

## Folder Structure

`Assets/Horoyoel/` structure:

![Mod01](/Manual_Pict/Mod01.png)

| Folder        | Description           |
| ------------- | --------------------- |
| Horoyoel      | Presets               |
| 01_FBX        | Model FBX             |
| 02_Materials  | Materials (lilToon)   |
| 03_Animations | Animator & animations |
| 04_Motions    | AFK motions           |
| 05_Menu       | Menu configs          |
| 10_Prefabs    | Individual prefabs    |

---

## Prefab Structure

All prefabs (except base) are Modular Avatar ready.

Use `Horoyoel.prefab` as the base.

![Mod02](/Manual_Pict/Mod02.png)

---

## Optimization Tip

Bone count can be reduced:
315 → 216 using AAO

![Mod03](/Manual_Pict/Mod03.png)
![Mod04](/Manual_Pict/Mod04.png)

---

## Prefab Components

![Mod05](/Manual_Pict/Mod05.png)

| No   | Component     | Description          |
| ---- | ------------- | -------------------- |
| 1    | Action Layer  | AFK motion           |
| 2    | FX Layer      | Chest & claw control |
| 3    | PhysBones     | Physics              |
| 4    | BodyMenu      | Body settings        |
| 5    | FaceEmoPrefab | Expression control   |

---

## Expression Modification

Uses FaceEmo.

---

### Point 1: Restore Menu

- Place prefab
- Menu → FaceEmo → Restore Menu

![FaceEmo1](/Manual_Pict/FaceEmo1.png)

Select:
`Assets/Suzuryg/FaceEmo/BackupFaceEmo_Horoyoel.asset`

![FaceEmo2](/Manual_Pict/FaceEmo2.png)

Success:

![FaceEmo3](/Manual_Pict/FaceEmo3.png)

Error fix:
Rename prefab to "Horoyoel"

![Error1](/Manual_Pict/Error1.png)

---

### Point 2: Object References

Set references correctly in FaceEmo.

Otherwise:
- Tongue stuck
- Eyes not switching
- Expressions fail

![FaceEmo4](/Manual_Pict/FaceEmo4.png)

---

### Point 3: Without FaceEmo

Delete:

`FaceEmoPrefab`

Then use your own Animator/Menu.
