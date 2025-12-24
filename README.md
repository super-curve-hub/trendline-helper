# trendline-helper
できること（MVP）
・チャート画像をアップロード
・価格スケールを2点キャリブレーション（軸の任意2点をクリック→価格入力）
・「いま（最新足）」のX位置をクリック  
・Action Lineを2点クリックで定義  
・Safety Lineを2点クリックで定義  
　（任意）現在値をクリック（または手入力）  
 　バッファ（buf / bufS）、R倍率、Rmaxを入力 
  出力：  Long/Short別に Entryトリガー / Stop / TP（1R,1.5R,2R）  
  低リスク判定（Risk &lt;= Rmax）  
  すでにブレイク済みか（現在値がトリガー超えたか）
