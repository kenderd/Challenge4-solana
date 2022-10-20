Upon Observing the difference between the way transactions were created in the Hello World example vs the Break example,

Here are the things I've noticed.

functions that actually create the transactions were segmented from the Create.tsx file in Break.
It was later then imported to Create.tsx to consolidate everything, if I'm not mistaken. I observed the transactions having to pass through three files coming initially from create-transaction-worker-script.ts. Im honestly unfamiliar with the ways in this, but I infer that these "workers" and "providers" are components of the development architecture in this context.

I also don't know typescript and thanks to Metacrafters for giving me the opportunity to dip in it for the first time.
I heard that it's an object oriented language tho, so I think what's been happening is just a matter of inheriting classes

Break also utilizes blockhash and if I'm not mistaken, hello world doesnt. I remember Isabel mentioned that incorporating blockhash brings in
more security.

This can make me say that creation of transactions in Break is more complicated for good reasons and Hello World is much more straight forward.

Creation of accounts in the Break repo doesn't seem to be the exact same with what I've seen throughout the module.
Aside from it introducing more parameters, it also shows me more features such as creating Accounts in batch and closing accounts.

Seeing more from the repo only opens up my perspective more to what's possible.

Clearly, I can't explain everything well yet as it's hard to grasp everything at once, but I'm willing to stay and learn.
