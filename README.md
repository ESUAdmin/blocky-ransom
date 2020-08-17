# blocky-ransom

Decompiled C# ransomware by some random meme master 

dnSpy exported project source

## Threat Warning

Channel Title: 韩国N房间去中心化三网直搜索神器

Channel Username: NthRoomTorrent2

File SHA256: `454756725D005FCF54483BF6B6AE28E3966633728D6BD750D4E5236077487771`

Behavior: See [Form1.cs](https://github.com/ESUAdmin/blocky-ransom/blob/master/blocky/Form1.cs) @ `StartAction`

## File Recovery (theory)

The default random in C# is not crypto-secure and relies on an env called `TickCount`. The value is 32-bit and counts time in milliseconds.

If you know when the ransom is being run, you can brute-force the property to get the right password.
