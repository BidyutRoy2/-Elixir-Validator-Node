<h2 align=center>Elixir Validator Node Guide by Hidden Gem</h2>

<details>
<summary> <h1> Project Information </h1> </summary>
Elixir is a decentralized modular protocol aimed at enhancing liquidity on orderbook-based exchanges. It utilizes a decentralized proof-of-stake (DPoS) system, where validator nodes play a crucial role in maintaining the network’s accuracy and security. Validators are responsible for verifying transactions, creating new blocks, and participating in the consensus process to ensure the network operates smoothly. As part of the protocol's development, there is a potential for validator nodes to receive an airdrop during the TokenGeneration Event (TGE).

They raised $17.5M from VCs like Amber Group, Mysten Labs

</details>

![Screenshot 2024-09-03 103631](https://github.com/user-attachments/assets/0b6eba17-7aa1-46e2-8401-ae3a34dc25d2)


[Elixir Twitter](https://x.com/elixir) • [Elixir Discord](https://discord.gg/elixirnetwork) • [Elixir Docs](https://docs.elixir.xyz/)

<details>

 <summary>VPS Configurations </summary>

| **Component**         | **Recommended Specification**                |
|-----------------------|----------------------------------------------|
| **RAM**            | 8 GB RAM                                    |
| **Internet Connection** | Reliable 100 Mbit/s                        |
| **Disk Storage**      | 100 GB (minimal)                            |


</details>

- If you want, you can buy from [PQ Hosting](https://pq.hosting/?from=557648) using crypto currency

## One Click Installation Command
```bash
[ -f "elixir.sh" ] && rm elixir.sh; wget -q https://raw.githubusercontent.com/BidyutRoy2/Elixir-Validator-Node/main/elixir.sh && chmod +x elixir.sh && ./elixir.sh
```
- Now check your node status
```bash
curl "$(curl -s ifconfig.me):17690/metrics"
```
- You will see something like this
```bash
{"started_at":"2024-09-03 05:41:39","data_frame_version":"1.0.1","order_proposal_version":"1.0.1","app_version":"3.1.1","status":"authorized","data_frames_consumed":67,"proposals_produced":66}
```
- It means it's fine
- You can also check logs using the below command
```bash
docker logs elixir -f -n 500
```
- If you see something like this, It's fine

![image](https://github.com/user-attachments/assets/490e3195-bfc2-4bb9-af06-99467ae65bbd)

- Don't forget to save your `validator wallet address details`, use this command to see
```bash
cat validator_wallet.txt
```

# ▄︻デ𝙂𝙚𝙩 𝙇𝙖𝙩𝙚𝙨𝙩 𝘼𝙞𝙧𝙙𝙧𝙤𝙥𝙨 & 𝙐𝙥𝙙𝙖𝙩𝙚𝙨═━一

### ▄︻デ𝙅𝙤𝙞𝙣 𝙏𝙚𝙡𝙚𝙜𝙧𝙖𝙢═━一 [🎀  𝐻𝒾𝒹𝒹𝑒𝓃 𝒢𝑒𝓂  🎀](https://t.me/hiddengemnews) 

### ░▒▓█►─═  𝓗𝓲𝒹ᗪ𝓔η Ǥέ𝕄 ═─◄█▓▒░
