git init
git add .
git commit -m "flash loan attack"
git push origin main

## Patrick hinted to look for sandwitch attack here

This possibly means both frontrunning and backrunning?

<details>
In a frontrunning scenario, an attacker tries to exploit information about a pending transaction by placing their own transaction ahead of it. In contrast, in a backrunning or sandwich attack, the attacker positions their transactions both before and after the target transaction. This can be done to capitalize on the expected price movement caused by the target transaction.

Both _frontrunning_ and _backrunning_ are types of transaction order manipulation that can occur in decentralized systems, particularly in blockchain networks where transactions are publicly visible before being confirmed in a block.

It's essential for participants in these systems to be aware of potential front and backrunning risks and employ strategies to mitigate them, such as using techniques like transaction batching or utilizing privacy features if available.

</details>
