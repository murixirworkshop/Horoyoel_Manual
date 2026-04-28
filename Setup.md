# 導入方法(VRChatへのアップロード)

## **1. 事前準備**  

- [Unity(2022.3.22f1)](https://unity.com/ja/download)をダウンロード・インストールしてください。

- **[VRChat Creator Companion](http://vrchat.com/home/download)** **(VCC)** を導入してください。

  ![image-20250907185325640](Manual_Pict/VCC0.png)

## **2. 必須パッケージの追加**  

- 以下のパッケージをVCC経由で導入します。
  - **必須パッケージ**  
    - [lilToon](https://lilxyzw.github.io/lilToon/)  のウェブページから「VCCに追加」を選択し、画面の案内に従ってAdd Repositoryを行ってください。
    - [FaceEmo](https://suzuryg.github.io/face-emo/ja/)  のウェブページから「ダウンロード(VCC)」を選択し、画面の案内に従ってAdd Repositoryを行ってください。
    - [Modular Avatar](https://modular-avatar.nadena.dev/ja)  のウェブページから「ダウンロード」を選択し、画面の案内に従ってAdd Repositoryを行ってください。

## 3. **VCCで新規プロジェクトの作成**

画面右上のCreate New Projectから新規プロジェクトを作成してください。

![image-20250907190359795](Manual_Pict/VCC1.png)

続いて表示される画面でUnity2022 Avatar Projectを選択し、プロジェクト名を任意に設定してCreate Projectからプロジェクトを作成してください。

![image-20250907185816115](Manual_Pict/VCC2.png)

## 4. 必須パッケージのインストール

プロジェクトが作成できたらまずManage Projectを選択します。

![image-20250907191227241](Manual_Pict/VCC3.png)

ここでlilToon, Modular Avatar, FaceEmoをインストールしてください。Not Installedのプルダウンメニューから最新版を選択するか、右端の(＋)を選択してインストールできます。

ここで必須パッケージが表示されない場合は、[2. 必須パッケージの追加](###_2-必須パッケージの追加)をやり直してください。

最終的に以下のようにlilToon, Modular Avatar, FaceEmoがインストールされた状態になればOKです。

![image-20250907192752855](Manual_Pict/VCC7.png)

## 5. **ホロヨエル本体のインポート**  

- Open Projectを選択し、作成したプロジェクトを開いてください。Unityが起動します。

![image-20250907192931627](Manual_Pict/OpenProject.png)

- Unity のメニューから **Assets → Import Package → Custom Package** を選択。  

![image-20250907193231728](Manual_Pict/Unity1.png)

- 配布ファイル **`HoroyoelVerXXX.unitypackage`** を指定してインポートしてください。（xxxにはバージョン名が入ります）。

  Importを選択し、インポートします。

![image-20250907193733475](Manual_Pict/Unity2.png)

- インポートが完了すると `Horoyoel` フォルダがアセットに追加されます。

## 6. **シーンに配置**  

- 以下のいずれかの Prefabを **Hierarchy** にドラッグ＆ドロップしてください。  
  - Assets/Horoyoel/Horoyoel_PresetA  (天使の服を着たホロヨエル)
  
  - Assets/Horoyoel/Horoyoel_PresetR  (ルームウェアを着たホロヨエル)
  
    ![image-20250907193847044](Manual_Pict/Unity3.png)
  
    成功するとホロヨエルがシーンに置かれます。
  
    ![image-20250907193930926](Manual_Pict/Unity4.png)

## 7. **アップロード**  

- Unity のメニューからVRChat SDK -> Show Control Panel で VRChat SDK の Control Panel を開き、VRChatのIDでログインしてください。

  ![image-20250907195120702](Manual_Pict/SDK1.png)

- ログインするとBuilderタブからAvatarの情報を入力できるようになります。Name, Visibility, サムネイルを設定してアップロードします。

> ⚠️ <span style="color:red; font-weight:bold;">注意</span>  
> Visibility の項目は <span style="color:red; font-weight:bold;">必ず Private</span> に設定してください。  
> Public に設定するのは <span style="color:red; font-weight:bold;">規約違反</span> です！

![image-20250907200200691](Manual_Pict/SDK2.png)

- → Build から **Build & Publish**を実行。  

- アップロードを完了させます。お疲れ様でした！