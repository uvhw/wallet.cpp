# wallet.cpp
https://uvhw.github.io/bitcoin/
Latest revision as of 2022-02-08T05:12:35
TENTATIVE semantic version number	Software release	Change type	BIP(s)
0.1.0	wxBitcoin 0.1.0	original
0.2.0	wxBitcoin 0.1.6	softfork	added nLockTime enforcement[1]
0.2.1	wxBitcoin 0.3.1	softfork	mostly-redundant 1 MB block size limit
0.2.2	wxBitcoin 0.3.5	softfork	fixes CVE-2010-5141
0.2.3	wxBitcoin 0.3.6	softfork	OP_NOPs made explicit
0.3.0	wxBitcoin 0.3.7	hardfork	scriptSig + scriptPubKey evaluations separated [2]
0.3.1	wxBitcoin 0.3.10	softfork	fixes CVE-2010-5137 and CVE-2010-5139
0.3.2	wxBitcoin 0.3.12	softfork	fixes CVE-2010-5138
0.3.3	wxBitcoin 0.3.13	softfork	Treat multisig with more than 20 keys invalid after block 84000 [3]
1.0.0	Bitcoin Core 0.6.0	softfork	fixes CVE-2012-1909
1.1.0	Bitcoin Core 0.6.0	softfork	BIP16
1.1.1	Bitcoin Core 0.7.0	softfork	BIP34
1.1.2	Bitcoin Core 0.8.1	softfork	fixes CVE-2013-3220 by adding txid change limit
2.0.0	Bitcoin Core 0.8.1	hardfork	removed BDB lock limit & txid change limit
2.0.1	Bitcoin Core 0.9.2	softfork	BIP42
2.1.0	Bitcoin Core 0.10.0	softfork	BIP66
2.2.0	Bitcoin Core 0.10.4	softfork	BIP65
2.3.0	Bitcoin Core 0.12.1	softfork	BIP68, BIP112, BIP113
2.4.0	Bitcoin Core 0.13.1	softfork	BIP141, BIP143, BIP147
2.4.1	Bitcoin Core UASF 0.14.0	softfork	BIP148
2.4.2	Bitcoin Core 0.16.3	softfork	fixes CVE-2018-17144
2.5.0	Bitcoin Core-based Taproot Client 0.21.0	
