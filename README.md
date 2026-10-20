# William Stanley Jevons

Long consideration of the exchanges of the present age has led me to the opinion that their chief defect lies not in their prices, but in their concealment. The trader cannot see the rules by which orders are filled, nor examine the account which is kept against them; they are asked to trust where they ought to be able to verify. I occupy myself, therefore, with the construction of exchanges in which every rule may be read, every transaction is recorded in public, and every balance may be proved by calculation.

---

### monkeytrading

My present undertaking is [monkeytrading](https://github.com/0xjevons/monkeytrading), an open-source engine for contracts for difference upon crypto-assets, currencies, indices, commodities, and shares.

* **The house.** The exchange itself stands as counterparty to every contract, and the ownership of the house is distributed among those who trade with it, no portion being reserved beforehand for its founders or their friends.
* **The terms.** A contract is filled at once, at the median price of several independent markets. The trader who loses pays no charge; the trader who gains surrenders a fixed share of the profit.
* **The custody.** Collateral rests in a public contract upon the chain, which pays out upon instructions signed by the engine, and, should the engine fall silent, to any trader who proves their balance.

---

### Method

* **Determinism.** The engine is a strict function of the commands it receives. The same record, replayed upon any machine, yields the same state to the last fraction of a cent.
* **Publicity.** Every command and its consequence is published as it occurs, and the state is periodically signed and posted upon the chain, so that any reader may replay the record and verify the sum.
* **Confinement.** The engine runs within a confidential-computing enclave, whose code anyone may rebuild and attest against the published source. It is written in Rust.
* **Equality.** Every participant is bound by the same published rules; none enjoys a private channel, nor any prior claim upon the order of execution.

The engine is at present conducted by a single operator. When its working has been sufficiently proved, that office shall pass by election to operators chosen by the holders of the house's equity.

---

### Principle

> "Repeated reflection and inquiry have led me to the somewhat novel opinion, that value depends entirely upon utility."
> — *The Theory of Political Economy*, 1871

A market can attain its greatest utility only when its rules are fixed in advance, open to every inspection, and enforced by no discretion but that of calculation. The code is the statement of those rules; the public record is their proof.

---

### Communications

* Cryptographic Dispatch: william.jevons@proton.me
* Public Log: [@0xjevons](https://x.com/0xjevons)
* Network Interface: [@jevons_0x](https://t.me/jevons_0x)
