# zk-Crush

zk-Crush is a way to tell your crush you like them with [zero-knowledge](https://en.wikipedia.org/wiki/Zero_knowledge#:~:text=Zero%20knowledge%20may%20mean%3A,the%20veracity%20of%20the%20statement).

### How it works

The idea is that we hash the name of your crush, then people can hash their name and check if their hash matches the hash of the crush you've provided. Therefore it's zero-knowledge because we don't store your name, we only know the hash, so finding a hash that matches corresponds to knowing the pre-image to the hash. Also note that this is entirely client-side, we store nothing on a server.

### How to use it

Very simple, you enter your name and the name of a crush.

It will generate a URL that you will be able to publicly share.

When people go to this URL, they can enter their name, to generate the hash of their name and see if it matches the hash of your crush. If it doesn't, no harm done, if it does, they now know!
