---
author: Moon
date: '2020-04-23T07:00:00.000Z'
title: 'Polygon'
description: 'Hướng dẫn sử dụng Polygon'
contributors:
  - "moon14888"
---

Chào mấy fen! Bạn đã nghe đến việc dịch chuyển đến Polygon (trước đây là Matic) đúng không, những bạn có biết rõ ràng nó là gì chưa nhỉ? Đừng lo, bọn mình sẽ giúp bạn vượt qua từng bước một!

Nói một cách ngắn gọn, Polygon là giải pháp mở rộng Layer 2 của những blockchain công khai trên Ethereum. Nó là một nền tảng phi tập trung giúp đảm bảo các giao dịch trở nên nhanh hơn và phí giao dịch sẽ cực kỳ rẻ với khả năng hoàn thành ngay trên chuỗi. Nếu bạn muốn có thêm nhiều thông tin, hãy xem qua [bài viết này](https://medium.com/matic-network/what-is-matic-network-466a2c493ae1).

Hãy vẫy tay chào tạm biệt phí giao dịch lên đến 100 đô trên Uniswap và cùng chào đón những tương tác (gần như miễn phí) trên ngôi nhà mới nhé!

<div class="contentsBox">

**Nội dung**

<ol>
<li><a href=#why-polygon->Tại sao lại dùng Polygon?</a></li>
<li><a href=#adding-polygon-to-your-metamask>Thêm Polygon vào Metamask</a></li>
<li><a href=#bridging-assets-to-polygon>Kết nối tài sản đến Polygon</a></li>
<li><a href=#bridging-assets-back-to-ethereum-mainnet>Chuyển tài sản về lại Ethereum Mainnet</a></li>
</ol>

</div>

## Tại sao lại dùng Polygon?

Aavegotchi Mainnet xém tí được triển khai vào ngày 4 tháng Giêng 2021 rồi đấy. Ngày hôm đó Bitcoin tăng gần 40%, khiến cho mấy con bot kiếm lợi nhuận chênh lệch bị loạn mạch chủ. Đều này khiến cho giá gas tăng phi mã lên 400 gwei, khiến phí giao dịch nhìn mà mắc hờn. Để mình lấy một ví dụ cho bạn dễ hiểu: Chi phí để mở và triệu hồi Gotchi từ duy nhất 1 [portal](/portals) sẽ ngốn của bạn ít nhất 300 đô la.

Rõ ràng là game có thể được khởi chạy trên Mainnet của Ethereum. Nhưng bởi Polygon đang làm việc cùng với những dự án NFT khác (ví dụ như Opensea) rồi nên lựa chọn này cũng dễ hiểu. Cộng đồng đã thể hiện quan điểm của mình và 76% trong số họ đã bỏ phiếu để game được triển khai trên Polygon.

For an extended discussion on this topic, see this medium [post](https://aavegotchi.medium.com/why-aavegotchi-chose-polygon-356238977fb2).

## Thêm Polygon vào Metamask

Let’s get started with the fun stuff! To use Polygon, you first need to add it to your Metamask wallet.

1). Open the extension and click the “Ethereum Mainnet” button on the top.

<img class = "bodyImage" src = "/polygon/metamask.png" alt = "Metamask" />

2). Chọn “Custom RPC”.

<img class = "bodyImage" src = "/polygon/metamask-custom-RPC.png" alt = "Metamask Custom RPG" />

3). Nhập thông tin này vào:

Network Name: Matic Mainnet

New RPC URL: https://rpc-mainnet.maticvigil.com/

Chain ID: 137

Currency Symbol (optional): MATIC

Block Explorer URL (optional): https://explorer.matic.network/

Một khi bạn đã thêm vào xong xuôi, hãy nhấp "Save".

4). There’s no step four, you’re already done! You can now switch between Ethereum Mainnet and Polygon by clicking the button from step 1.

## Kết nối tài sản đến Polygon
Alright you got Metamask set up and are ready to dive right in. But before you need some assets on Polygon. We’re going to use the [Proof of Stake (PoS)](/glossary#proof-of-stake) Polygon Bridge to transfer our funds from Ethereum Mainnet to Polygon. If you only want to transfer your GHST, ignore all of the following steps and use our simple Aavegotchi Bridge [here](https://aavegotchi.com/bridge).

So for everyone who wants to transfer different assets, such as ETH or USDC, here’s how you do it:

1). Head over to [https://wallet.matic.network/](https://wallet.matic.network/) and login with Metamask. Make sure you’re in the “Wallet” tab, it should look something like this:

<img class = "bodyImage" src = "/polygon/matic-wallet.png" alt = "Matic Wallet" />

2). **DO NOT** click the “Switch to Plasma” button. That’s the wrong bridge and needs 7 days to withdraw. Instead add the asset you want to transfer on the right side. I have already added USDC so you can see it in my wallet.

<img class = "bodyImage" src = "/polygon/matic-wallet-add-token.png" alt = "Adding Token to Matic Wallet" />

3). On the left side click “Matic Wallet” and “Deposit”.

<img class = "bodyImage" src = "/polygon/matic-wallet-deposit.png" alt = "Depositing Token to Matic Wallet" />

4). Click “Continue to Deposit” and select your asset here:

<img class = "bodyImage" src = "/polygon/matic-wallet-deposit2.png" alt = "Depositing Token to Matic Wallet" />

5). Enter how much of it you’d like to bridge and click the big blue button.

<img class = "bodyImage" src = "/polygon/matic-wallet-deposit3.png" alt = "Depositing Token to Matic Wallet" />

Aaaaaand that’s it! Just confirm the transaction in Metamask and you’re done. It can take up to 10 minutes for the tokens to arrive in your Polygon address. You should get 0.1 MATIC airdropped if you transfer a stablecoin and open [Quickswap](https://quickswap.exchange/), the largest DEX on Polygon. (That’s enough for 1000s of transactions, Polygon is aavesome!)

If you need help with anything you can join the Aavegotchi [Discord](https://discord.com/invite/rttCTkZ) and ask a fellow community member.

## Chuyển tài sản về lại Ethereum Mainnet

What about bridging our assets back to Ethereum Mainnet? Is there a way to do it?

Yes, there is a way to transfer your assets back to Ethereum Mainnet!

Head over to the [Aavegotchi Bridge](https://aavegotchi.com/bridge) again.

<img class = "bodyImage" src = "/polygon/bridge-to-matic.png" alt = "Aavegotchi Bridge" />

At the right hand side of the screen, there is an image of a token as well as a box where you can input an amount in. Click on the image of the token and a display of available tokens will appear. Select the [maToken](/matokens) which you want to bridge back to Ethereum Mainnet. After that, key in the desired amount in the box and hit the "Transfer to Ethereum" button.

Withdrawing from Polygon takes approximately 30 minutes. Sometimes, it might take longer. After the withdrawal is complete, you still need to click the "CLAIM ON ETHEREUM" button to get your tokens back on Ethereum Mainnet.

Currently, the Aavegotchi Bridge supports the transfer of maTokens from Polygon to Ethereum Mainnet. In time to come, it will support Aavegotchis (ERC-721) and Wearables (ERC-1155) as well.