- Der er en ledger, der holder styr på accounts. HVer Peer har en kopi af denne ledger
- Hver account har en balance (Så der er et Map fra String -> int)
- Alle peers i netværket har på et tidspunkt den samme Ledger
- Der kan laves en transaktion på netværket.
- En transaktion består af en amount (int), en From og To (String)
- Amount bliver overført fra From -> To
- Når en peer lave en transaktion, opdaterer den sin ledger. 
- efter en opdatering a ledgeren, så floodes netværket med den nye ledger
- Alle peers har på et tidspunkt den samme ledger.
