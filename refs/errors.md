### 正誤訂正


#### 第1版第1刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|:--|---|:--|:--|:--|
|まえがき|ⅵ|2行目<br>(誤) 重要なな<br>(正) 重要な||2023-11-27|
|1章|p.2|下から2行目<br>(誤) 対応がづく<br>(正) 対応がつく||2023-11-27|

#### 第1版1～2刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|:--|---|:--|:--|:--|
|まえがき|v|17行目<br>(誤) 活用されてるかを含めてを紹介し<br>(正) 活用されているかを含めて紹介し||2023-12-12|
|1章|p.3|下から4行目<br>(誤) 意味を理解することでなく<br>(正) 意味を理解することではなく||2023-12-12|
|1章|p.19|コード1.11のキャプション<br>(誤) (コード1.3からコード1.6の一部を再掲)<br>(正) (コード1.5、1.6、1.8の一部を再掲)||2023-12-18|
|1章|p.19|コード1.11の7行目<br>(誤) ``x_samples = samples['prior']['x'].values``<br>(正) ``x_samples = prior_samples['prior']['x'].values``||2023-12-18|
|2章|p.50|3行目<br>(誤) に対応して<br>(正) に対応した||2023-12-12|
|4章|p.82|7〜8行目<br>(修正前)"2.4. Diagnosing Numerical Inference"<br>(修正後) |URLとしてはダブルクオートの内部は不要なのでなくします|2023-12-12|
|5章|p.97|6行目<br>(誤) なりますが。<br>(正) なりますが、||2023-12-12|
|5章|p.101|コード5.1.13の最終行<br>(誤) y_list = norm(x_list, mu_mean, sigma_mean)<br>(正) y_list = norm(x_list, mu_mean1, sigma_mean1)||2023-11-27|
|5章|p.102|2行目<br>(誤) mu_meanとsigma_mean<br>(正) mu_mean1とsigma_mean1||2023-11-27|
|5章|p.103|コード5.1.15の2行目<br>(誤) X_less = x_result[:5]<br>(正) X_less = X[:5]||2023-11-27|
|6章|p.209|コード6.3.12の13行目<br>(誤) x1 = summary_theta1['mean'].values<br>(正) x1 = summary_theta1['mean']|紙面の実装だと16行目の計算が標本標準偏差になってしまうため修正|2023-12-12|
|6章|p.209|コード6.3.12の18行目<br>(誤) df_sum1['能力値'] = x1<br>(正) df_sum1['能力値'] = x1.values|紙面の実装だと16行目の計算が標本標準偏差になってしまうため修正|2023-12-12|
|6章|p.209|実行結果<br>(コード修正前)<br><img src='../images/fig-06-03-12-before.png' width=200><br>(コード修正後)<br>　<img src='../images/fig-06-03-12-after.png' width=200>|能力値の列の値が上記コード修正に伴い多少変化します|2023-12-12|
|6章|p.211|コード6.3.15の下から2行目<br>(出版時) w3 = (w1 * b_mean1).sum(axis=1)/w2[0]<br>(現在) w3 = (w1 * b_mean1).sum(axis=1)/w2.iloc[0]|pandasのバージョンが上がるとワーニングが出ることがわかっているので、バージョンアップに備えて事前にコードを修正|2023-12-12|

#### 第1版1～3刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|:--|---|:--|:--|:--|
|4章|p.74|コード4.6 1行目<br>(誤)  pm.model_to_graphviz(model)<br>(正)  pm.model_to_graphviz(model1)||2024-01-06|
|6章|p.164|表6.1.1 5行目一番右<br>(誤) 1500<br>(正) 1600||2024-01-13|

#### 第1版1～4刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|:--|---|:--|:--|:--|
|1章|p.17|6行目<br>(誤)  samples['prior']<br>(正)  prior_samples['prior']||2024-02-18|
|2章|p.25|最終行<br>(誤)x_samplesを用いて<br>(正)x_samples1を用いて||2024-02-18|
|4章|p.83|コード4.13 1行目<br>(誤)model_to_graphviz(model) <br>(正)model_to_graphviz(model2)||2024-02-18|
|5章|p.100|1行目<br>(誤)4章でも説明したとおり<br>(正)1.5.1項でも説明したとおり||2024-02-18|
|5章|p.101|3行目 <br>(誤)mu_meanとsigma_mean<br>(正)mu_mean1とsigma_mean1||2024-02-18|
|5章|p.155|1行目 <br>(誤)コード5.4.15の4行目<br>(正)コード5.4.15の5行目||2024-02-18|
|6章|p.210|コード6.3.13 1行目 <br>(誤)df_sum['偏差値'], df_sum['能力値']<br>(正)df_sum1['偏差値'], df_sum1['能力値']||2024-02-18|

#### 第1版1～5刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|:--|---|:--|:--|:--|
|5章|p.152|コード5.4.13の28行目、29行目 <br>(誤)<br>``ax.get_lines()[0].set_label('KDE versicolor')``<br>``ax.get_lines()[1].set_label('KDE virginica')``<br>(正)<br>``ax.get_lines()[1].set_label('KDE versicolor')``<br>``ax.get_lines()[0].set_label('KDE virginica')``||2024-03-11|
|5 章|p.152|コード5.4.13の実行結果(グラフ)<br>(誤)<br><img src="../images/fig-05-04-13-ng.png"><br>(正)<br><img src="../images/fig-05-04-13-ok.png">||2024-03-11|


<hr>

[メインページに戻る](../README.md)
