<p><a href="http://www.kalkulus.trade/"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://i.imgur.com/TDhrEOP.png" /></a>&nbsp;</p>
<p><strong>Kalkulus GUI Client Raspberry PI3 Official Repository</strong></p>
<p>This repository is designed to work on a Raspberry PI3 with Gentoo 64Bit.<br />After compilation you will have a working and full functional KLKS GUI wallet with staking and masternodes controller functionalities.</p>
<p>You can download a compiled GUI wallet from official release page: <strong><a href="https://github.com/kalkulusteam/klks/releases/tag/v2.5.1">https://github.com/kalkulusteam/klks/releases/tag/v2.5.1</a>&nbsp;</strong>or you can follow instructions below to compile wallet in your Linux system (ubuntu 16.04 recommended with all typical deps installed)</p>
<p><strong>To compile GUI wallet:</strong></p>
<p>Clone this repo on your computer, open terminal, install missing deps and compile:</p>
<table class="highlight tab-size js-file-line-container" data-tab-size="8">
<tbody>
<tr>
<td id="file-klks_qt-rasp-LC3" class="blob-code blob-code-inner js-file-line">sudo apt-get install curl g++-aarch64-linux-gnu g++-4.8-aarch64-linux-gnu gcc-4.8-aarch64-linux-gnu binutils-aarch64-linux-gnu g++-arm-linux-gnueabihf g++-4.8-arm-linux-gnueabihf gcc-4.8-arm-linux-gnueabihf binutils-arm-linux-gnueabihf g++-4.8-multilib gcc-4.8-multilib binutils-gold bsdmainutils</td>
</tr>
<tr>
<td id="file-klks_qt-rasp-L4" class="blob-num js-line-number" data-line-number="4">
<div class="message first">
<div class="body">
<div class="message-text">
<div class="markup">cd klks</div>
<div class="markup">chmod 777 -R *</div>
<div class="markup">cd depends</div>
<div class="markup">make HOST=aarch64-linux-gnu</div>
</div>
</div>
</div>
<div class="message">
<div class="body">
<div class="message-text">
<div class="btn-reaction">cd ..</div>
<div class="btn-reaction">chmod -R 777 build-aux/m4 <br />./autogen.sh</div>
<div class="btn-reaction">./configure --prefix=`pwd`/depends/aarch64-linux-gnu --enable-static <br />sudo make HOST=aarch64-linux-gnu</div>
<div class="btn-reaction">&nbsp;</div>
<div class="btn-reaction">First time you open the GUI wallet, launch wtih:<br />./klks-qt &amp;</div>
<div class="btn-reaction">&nbsp;</div>
</div>
</div>
</div>
&nbsp;</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<div class="message first">&nbsp;</div>
<div class="message">
<div class="body">
<div class="message-text">
<div class="btn-reaction">&nbsp;</div>
<div class="btn-reaction">***********************************************************************************</div>
</div>
</div>
</div>
<p><strong>Main Features:</strong></p>
<ul>
<li><strong>Masternode technology</strong> used to secure the network</li>
<li><strong>See-Saw Reward Mechanism: </strong>dynamic block reward allocation between masternodes and staking.</li>
<li><strong>Governance Budgeting System: </strong>10% of each block reward goes to a fund for allows node operators to vote on important proposal about developments within the blockchain. (Only when active)</li>
<li><strong>SwifTX</strong> for fast transactions with guaranteed zero confirmation.</li>
<li><strong>Obfuscation protocol</strong> for anonymized transactions using coin mixing technology.</li>
</ul>
<p>More information at <a href="http://www.kalkulus.trade" target="_blank" rel="noopener">http://www.kalkulus.trade</a></p>
<p>&nbsp;</p>
<p><strong>Coin Specs</strong></p>
<table>
<tbody>
<tr>
<td><strong>Ticker Symbol</strong></td>
<td>KLKS</td>
</tr>
<tr>
<td><strong>Algorithm</strong></td>
<td>Quark</td>
</tr>
<tr>
<td><strong>Type</strong></td>
<td>Proof-of-Stake</td>
</tr>
<tr>
<td><strong>Block Time</strong></td>
<td>120 seconds [POW] / 60 seconds [POS]</td>
<td>&nbsp;</td>
</tr>
<tr>
<td><strong>Masternode Collateral</strong></td>
<td>20000 KLKS</td>
</tr>
<tr>
<td><strong>Max Coin Supply</strong></td>
<td>20 Million Coins</td>
</tr>
<tr>
<td><strong>Premine</strong></td>
<td>9 Million coins to perform swap</td>
</tr>
<tr>
<td><strong>Block Reward</strong></td>
<td>15 KLKS each block until total coin supply is reached</td>
</tr>
<tr>
<td><strong>Reward Method</strong></td>
<td>See-Saw Reward Mechanism</td>
</tr>
<tr>
<td><strong>Governance Budgeting System</strong></td>
<td>10% of any block will go to the Governance Budgeting System (when active)</td>
</tr>
<tr>
<td><strong>RPC &amp; P2P Ports&nbsp;</strong></td>
<td>51122 / 51121</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p><strong>PoW/PoS Block Reward Scheme</strong></p>
<table>
<tbody>
<tr>
<td><strong>Proof Of Work Phase</strong></td>
<td>1-4999 Blocks.</td>
</tr>
<tr>
<td><strong>Proof of Stake Phase</strong></td>
<td>5000-infinite</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p><strong>Staking Methods</strong></p>
<table>
<tbody>
<tr>
<td><strong>Masternodes</strong></td>
<td>Yes - 20k KLKS Required</td>
</tr>
<tr>
<td><strong>Wallet Staking</strong></td>
<td>Yes - 1 to infinite klks</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p><strong>Links</strong></p>
<table style="width: 375px;">
<tbody>
<tr>
<td style="width: 93px;"><strong>Twitter</strong></td>
<td style="width: 270px;">https://twitter.com/kalkulus_team</td>
</tr>
<tr>
<td style="width: 93px;"><strong>Discord Chat</strong></td>
<td style="width: 270px;"><a href="https://discord.gg/UHDWDKT">Discord chat</a></td>
</tr>
<tr>
<td style="width: 93px;"><strong>Website</strong></td>
<td style="width: 270px;"><a href="http://kalkulus.trade/">http://www.kalkulus.trade</a></td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>&nbsp;</p>
