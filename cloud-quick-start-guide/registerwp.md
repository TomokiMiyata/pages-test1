# デバイスを登録する（Work Profile）

初回電源投入時の初期設定を終えた（あるいは既に個人として利用中の）、Google Playが利用可能な状態のAndroidデバイスを用意します。このデバイスをMobileIron Cloudに登録することにより、仕事の領域（Work Profile）が作成され、その中で仕事のアプリを利用できるようになります。  

Google Playから「MobileIron Go」アプリをインストールして開きます。  
![](images/748E3AD2-25BE-490F-86D3-3CCA36B9B993.jpg)

MobileIronのロゴの後、プライバシー声明が表示されます。続行をタップ。  
![](images/624318E9-0194-4023-A5A2-3A34DC1A69F5.png)

MobileIron Cloudに作成したユーザーのユーザーIDを入力します。  
![](images/6E9A31E0-CD79-45B4-A9C1-B0149AEA668C.png)

続いてこのユーザーのパスワードを入力し「サインイン」ボタンを押します。  
![](images/EFD42675-38B6-4CBC-9573-289B0473A3FC.png)

ユーザーの認証が完了し、仕事領域のセットアップが始まります。  
![](images/898B79B4-118A-4F7D-BBC2-DCDDCC0BDE9D.png)
![](images/747B46AA-9274-44C7-9910-403D40ABEEAF.png)
![](images/5FD58D4F-2B58-4372-B03B-80D01F0177E6.png)

画面ロックが設定されていない、あるいはMobileIron Cloudで設定したパスコードポリシーよりも弱い場合、画面ロックを設定するよう求められます。  
![](images/F9C113CE-117D-4928-BAD9-D62906666861.png)

画面ロックを設定する場合、Android OSの設定アプリの画面へ遷移します。PINやパスワードなど、ポリシーを満たす画面ロックを設定し、完了したら「←」でMobileIron Goアプリに戻ることができます。  
![](images/1A2DF9C9-C670-4287-88C6-3E7B1C2691AB.png)

他にユーザー操作が必要な設定が配布されていなければ、これでデバイス登録時の作業は完了です。  
![](images/8C6EA08D-C3D7-4719-9A87-7B6B4533AC2E.png)

ホームスクリーンにWorkフォルダが作成され、仕事のアプリが利用できるようになりました。  
※Workフォルダが作られるかどうか、またApp Catalogで設定した以外のアプリがデフォルトで含まれるかどうかはデバイスの機種やAndroidバージョンにより異なります。  
![](images/5D46BAD2-2557-4F13-801E-5378B6FB2210.jpg)
![](images/4354435D-FA64-4D5F-A804-4FFE873E0CBE.jpg)

仕事のGoogle Playを開くと、App Catalogで配布の設定を行なったアプリだけが表示されており、それ以外のアプリをユーザーが勝手にインストールすることはできません。  
![](images/5057CEA0-36F0-475F-AB3C-E78150FD0F3E.jpg)

またGoogle Playアカウントの氏名にはMobileIron Cloud上のユーザー名が反映されています。  
![](images/DF5FBCF1-12B5-4AC6-AB61-CF28C6B18648.jpg)

MobileIron Cloud側でも登録されたデバイスのレコードが確認できます。青字になっているユーザー名をクリックすると詳細が表示されます。  
![](images/2137A8DE-2526-4513-8693-5C9D7F9149FF.png)
![](images/E81E12CC-C0DD-46BE-8654-77AABF6CA32F.png)
