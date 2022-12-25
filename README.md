# vcCreateAPI
Using https://github.com/mattrglobal/bbs-signatures

# Usage

Throw a POST request to the following URL


//To create VP...
http://domain:3000/create_vc


input---<br>
publicKey: Issuer's publicKey<br>
secretKey: Issuer's secretKey<br>
messages: messages<br>

output---<br>
proof: proofValue of a VC

※This API does not strictly generate VCs.<br>
※You get only the proofValue
