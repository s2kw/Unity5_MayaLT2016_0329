Maya_PBR_SD_unitychanの収録シーンについて
2015/03/12 N.Kobayashi

【はじめに】
Maya_PBR_SD_unitychanは、PBR用にマテリアルを１つにまとめたSDユニティちゃんのシーンですので、シェーダー自体はMayaのLambertシェーダーです。

【収録されているシーンについて】
３つのシーンが含まれています。

●PBR_SDunitychan_Generic.mb
3dsMaxからなるべく素直にMayaに移植したモデルシーンです。
3dsMax由来のアニメーションデータがそのまま流せるようになっています。
ブレンドシェイプは3dsMaxのモーファーからモーフを移植し、Maya上で再設定してあります。

●SD_unitychan_motion_generic.mb
PBR_SDunitychan_Generic.mb用のモーションデータです。
3dsMax上で作成されたもので、揺れ物のアニメーションもついています。

No.   Start End   タイトル     メモ
1     0     1     Stance      スタンスポーズ
2     10    70    Standing    ループ
3     80    116   Walking     ループ
4     130   154   Running     ループ
5     170   238   Jumping     ループ
6     238   280   Damaged     ループ
7     280   360   GoDown      7⇒8でループ
8     361   404   DownToUp 
9     404   510   KneelDown   9⇒10でループ
10    511   520   KneelDownToUp  
11    520   590   Salute      敬礼！ループなし
12    170   194   JumpToTop   
13    194   238   TopToGround 
14    593   595   TopOfJump   194と同じフレーム


●PBR_SD_unitychan_humanoid.mb
Mecanim/Humanoid用のスケルトン構造を持っているモデルです。
腰（Hip）から上半身と下半身が出ている構造です。


