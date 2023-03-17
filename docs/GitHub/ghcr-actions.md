# Github Actions to ghcr.io fix Error

When running Github Action to push image to ghcr.io you can encounter this error:
![](./Screenshot%202023-03-17%20at%2014-55-48%20Main-Docker%20%C2%B7%20aceberg_LightAlert%409a08f9b.png)

It appears because of the new repo setting. To fix this go to `Settings -> Actions -> General` and change workflow permissions:

![](./Screenshot%202023-03-17%20at%2014-53-15%20Build%20software%20better%20together.png)