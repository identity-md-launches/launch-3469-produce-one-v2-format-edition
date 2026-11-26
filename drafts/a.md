OPEN INTEREST
Daily brief, format v2. Thursday, 26 November 2026.

LEAD: Braiins exposes an attack that steals miners' work without breaking into their machines.

An attacker redirected more than 1,000 mining sites to an impostor pool, Braiins disclosed on 25 November 2026. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] Their machines kept working while somebody else collected the credit. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1]

Braiins says four episodes on 20 November 2026 hit mainly European sites. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] Each diverted between 0.6 and 1.9 exahashes per second, its measure of mining power, for six to 49 minutes. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] Episodes recorded between 7 and 12 November 2026, mainly in Brazil and Argentina, affected 120 to 400 sites. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1]

Attackers advertised a more specific internet route covering the pool's address, according to the operator. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] Networks accepting that route sent miners to a proxy that submitted their work under the attacker's account. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1]

Braiins says neither its pool nor the mining machines were breached. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] Machines displayed normal activity; the pool dashboard showed the missing work. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] The report leaves the attacker and the total value of diverted rewards unidentified. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1]

The Stratum V2 project's documentation explains the transport problem: its protocol encrypts and authenticates traffic between miners and pools. [https://stratumprotocol.org/] Encryption conceals messages in transit; authentication lets a miner check the identity of the pool receiving its work. [https://stratumprotocol.org/] Together, the project says, they prevent intermediaries from substituting credentials to redirect mining credit. [https://stratumprotocol.org/]

The documentation also describes a privacy benefit from concealing mining traffic. [https://stratumprotocol.org/] Plain-text shares can reveal a miner's computing output and allow intermediaries to estimate earnings. [https://stratumprotocol.org/]

Braiins tested seven firmware implementations and found two widely used products accepting invalid TLS certificates. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1] An encrypted connection can still reach an impostor. [https://braiins.com/blog/bitcoin-hashrate-hijacking-unencrypted-stratum-v1]

NEWS:

[NEWS] SIX lists a bitcoin ETF with segregated Swiss custody.
SIX listed the Bitcoin Fund ETF, ticker BBIT, on 26 November 2026. [https://www.six-group.com/en/newsroom/media-releases/2026/20261126-bit-etf-issuer.html] Pernet von Ballmoos is the issuer; BIT Asset Management sponsors and manages the fund. [https://www.six-group.com/en/newsroom/media-releases/2026/20261126-bit-etf-issuer.html] The exchange says its bitcoin sits offline at a Swiss bank, separately from other assets, under Swiss collective investment law. [https://www.six-group.com/en/newsroom/media-releases/2026/20261126-bit-etf-issuer.html]

[NEWS] A Bitcoin reserve bill reaches the House calendar with a proposed sale ban.
The reported text of H.R. 8957 places it on the Union Calendar after committee reporting on 24 November 2026. [https://www.govinfo.gov/content/pkg/BILLS-119hr8957rh/html/BILLS-119hr8957rh.htm] Section 5 would prohibit selling or otherwise disposing of reserve bitcoin for at least 20 years from enactment. [https://www.govinfo.gov/content/pkg/BILLS-119hr8957rh/html/BILLS-119hr8957rh.htm] The text remains a bill; its calendar entry records a procedural advance, not enactment. [https://www.govinfo.gov/content/pkg/BILLS-119hr8957rh/html/BILLS-119hr8957rh.htm]

[NEWS] France's Senate rejects a declaration requirement for self-held crypto wallets.
The Senate lists amendment I-2447, filed on 23 November 2026, as rejected. [https://www.senat.fr/amendements/2026-2027/155/Amdt_I-2447.html] It would have required declarations for directly held cryptocurrency wallets worth at least €100,000 outside a cryptoasset service provider. [https://www.senat.fr/amendements/2026-2027/155/Amdt_I-2447.html] Its sponsors argued that existing foreign-platform account declarations leave an enforcement gap for assets held without intermediaries. [https://www.senat.fr/amendements/2026-2027/155/Amdt_I-2447.html]

TECH:

[TECH] Percolator reports an insurance-account fix after a bounty drain.
Anatoly Yakovenko invited attacks on Percolator on 25 November 2026. [https://www.nitter.cf/toly/status/2125740430545617199] Its repository says the first 70 USDC insurance bounty was drained on 26 November 2026 through stale data in a reused account. [https://github.com/aeyakovenko/percolator-cli]

The maintainers say a patch clears closed-account data and blocks the exploit, with another 70 USDC bounty open. [https://github.com/aeyakovenko/percolator-cli] The repository describes formal verification at the Lean programming-language level and explicitly says the experimental code has not been audited. [https://github.com/aeyakovenko/percolator-cli]

[TECH] Buterin takes hardware verification down to the chip's physical layout.
Vitalik Buterin published a chip-design walkthrough on 26 November 2026. [https://vitalik.eth.limo/general/2026/11/26/a_shallow_dive_into_open-source_chip_design.html] He follows a small circuit from public design code to the geometry used for manufacturing. [https://vitalik.eth.limo/general/2026/11/26/a_shallow_dive_into_open-source_chip_design.html]

He argues that inspecting a manufactured chip requires access to those layouts, alongside suitable inspection techniques. [https://vitalik.eth.limo/general/2026/11/26/a_shallow_dive_into_open-source_chip_design.html] His proposed split between performance hardware and secure hardware accepts lower efficiency in exchange for inspectability. [https://vitalik.eth.limo/general/2026/11/26/a_shallow_dive_into_open-source_chip_design.html]

CULTURE:

[CULTURE] Mert urges restraint as cryptography rumours spread.
On 25 November 2026, Mert questioned claims that AI laboratories had accelerated integer factorisation enough to threaten cryptocurrency systems. [https://www.nitter.cf/mert/status/2125641863948546231] He described the possible spillover into pairing-based cryptography as speculative, distinguishing it from attacks that directly expose wallet keys. [https://www.nitter.cf/mert/status/2125641863948546231] He favoured stronger cryptographic foundations while rejecting panic; his post supplied no demonstrated cryptographic break. [https://www.nitter.cf/mert/status/2125641863948546231]

[CULTURE] Venice's privacy policy permits retention under its anonymized label.
Venice's policy, effective 26 November 2026, says third-party providers may retain prompts sent to models marked Anonymized. [https://venice.ai/legal/privacy-policy] It separately prohibits retention beyond processing for models marked Private. [https://venice.ai/legal/privacy-policy]

Erik Voorhees promoted models available through Venice's API as fully private on 21 November 2026. [https://www.nitter.cf/ErikVoorhees/status/2124291053012586825] Read together, the policy and privacy page make that promise dependent on the model's label; neither establishes that any particular conversation was retained. [https://venice.ai/legal/privacy-policy] [https://venice.ai/privacy]

READING LIST:
[https://panteraresearchlab.xyz/research/2026-h1-report-flash-boys-or-superforecasters/] Danning Sui and colleagues separate Polymarket's users from its trading volume in their study of January through June 2026.
[https://www.syncracy.io/writing/social-trading-and-the-garden-of-eden] Ryan Watkins traces how trading activity becomes social content in his 27 August 2026 essay.
[https://multicoin.capital/2026/10/08/compute-capital-markets/] Shayon Sengupta's 8 October 2026 essay argues that markets for computing capacity must begin with physical delivery.

METHOD:
The 48-hour sweep ended at 10:42:44 UTC on 26 November 2026 and checked all 88 roster entries, official notices, legislation, repositories, authors' writing and open X mirrors; older context is dated. [https://raw.githubusercontent.com/openinterest-ai/paper/main/masthead/voices.csv] Rotation excludes editions 009–011 with no exception; selected roster voices were unquoted across the published archive. [https://openinterest.news/editions.html] Inaccessible pages supplied no claims; unverified Braiins loss totals, Venice breach allegations and founder-linked token-sale claims were cut; no published claim rests on secondary reporting.
