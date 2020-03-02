# デバイスを登録する（Fully Managed + Work Profile）

Android Enterpriseの Fully Managed + Work Profile モードでは、デバイスと仕事のアプリを会社で管理しながら、ユーザーが個人領域に好みのアプリをインストールして利用する自由も与えることができます。Fully Managed + Work Profile モードでのデバイス登録は、デバイスを工場出荷時にリセットした状態から行います。

初期状態のデバイスに電源を入れると「ようこそ」画面から初期設定が始まります。まずは通常通りに言語の選択やWiFiの設定を行います。  
![](images/73CF7606-B866-42B5-8A57-F9CF0466DBC2.png)

Googleアカウントへのログイン画面になったら、「afw#mobileiron.cloud」と入力します。  
![](images/860C76CF-BEE4-43ED-A869-0A047A66477C.png)

これにより、このデバイスがMobileIron Cloudで管理されることが認識され、MobileIron Goアプリのインストールが始まります。  
![](images/1D1D408F-622C-4D97-AA2F-A9CFF864EA95.png)
![](images/A10706DD-D197-451A-9E63-409D70D732B6.png)
![](images/8DA6F7E1-8B61-4B6E-90EE-80C02EE9EC0A.png)
![](images/BDCB5218-9571-4267-82F4-9FE8A8F57691.png)

初期設定が完了しホーム画面が表示された後、MobileIron Goアプリが自動的に起動します。この時点では未だMobileIron Cloudへのデバイス登録は完了していません。  
![](images/71BE7E8C-3CF8-44F5-AB42-35B29BC53313.png)

ここで戻るマークをタップしてもMobileIron Goを抜けてホーム画面に移ることはできません。MobileIron Goを終了した場合、デバイスは再び工場出荷時にリセットされます。  
![](images/3642287A-3CD1-41B1-B0FF-EBB857BA434D.png)

MobileIron Goのセットアップを続行すると、MobileIron Cloudユーザーでの認証を求められます。この先MobileIron Goアプリでの登録操作はWork Profileの場合と同じです。  
![](images/67570B58-7206-4C50-B18F-6B473DA339CB.png)

MobileIron Goアプリでデバイス登録操作が完了するとホーム画面へ移ることができます。  
![](images/A81208A7-EAEE-4C72-A8E2-0682748795B7.png)

アプリの一覧を見てみましょう。Work Profileモードで登録した場合と同様に、Playストアが２つあり、仕事のアプリと個人のアプリを領域を分けて利用することができます。また仕事のアプリには鞄のマークが表示されています。  
細かな違いですがFully Managed + Work Profileモードにおいてデバイス管理エージェントのMobileIron Goアプリには鞄のマークがありません。Work Profileモードと違い、MobileIron Goアプリがデバイス全体の管理権限を持っていることを示しています。  
![](images/00C95259-7C2E-4EA3-AFFE-61D0AD8417C3.png)

鞄マークのある仕事のPlayストアを開いてみます。MobileIron Cloudユーザーとして、管理者から配布されたアプリのみが利用可能であることがわかります。  
![](images/F6566C5F-52D5-4C08-984B-D0D376E643FD.png)

一方で鞄マークの無いPlayストアにはログインがされていません。ユーザーが個人のGoogleアカウントでログインすることで、通常のPlayストアから任意のアプリをデバイスの個人領域にインストールすることができます。  
![](images/018F97FF-1E9E-4592-89DF-5CBEC748A58D.png)
