### Advantages

Verifiable secret voting, having only to trust the organisation guardian

Alternative voting is supported de facto

### Election setup

For an election with N voters :

The Election Organisation N tokens are generated.

A list of the N token is generated and signed by the Election Organisation

The Election Guardian shuffle the tokens, then send one to each participant (eg: by mail, or by encrypting the token to the user public key).

(The Election Guardian can be an algorithm that has just to be run one time in a trusted setup)

### Election

Every participant publish his vote as (token, vote) using a mix network (eg: TOR, or a Ballot Box)

A the list of every vote is made public (and also may be signed by the Election Organisation).

Everyone can verify his vote and the result can be computed by a algorithm of our choice
