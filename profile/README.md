## Welcome to Kerberos.io 👋

Kerberos.io is a scalable video analytics and video management platform, build on top of Docker and Kubernetes, for everyone and everywhere. Kerberos.io comes with a range of tools allowing you to start small - home deployment, with a few cameras - and scale out to a large - enterprise deployment, with thousands of cameras.

It provides features to bring your own cloud (on-premise, hybrid, cloud), bring your own storage (ceph, minio, GCP, AWS, Azure, etc) and bring your own cameras (RTSP H264). You basicly run the show!

![Kerberos Enterprise Suite Introduction Youtube](https://github.com/kerberos-io/.github/assets/1546779/8257bd57-1dfe-4f31-98f1-e555ba5f3afd)

## A Kerberos.io architecture 📚

Within Kerberos.io we support containerisation by default. This means that any solution you'll find below is shipped as a container on the platform you desire: Docker, Docker Compose, Kubernetes, OpenShift, as a static binary through various package manager such as Snap.

Each component in the architecture can be installed where you want and combined.

- [Kerberos Agent](https://github.com/kerberos-io/agent)
- [Kerberos Factory](https://github.com/kerberos-io/factory)
- [Kerberos Vault](https://github.com/kerberos-io/vault)
- [Kerberos Hub](https://github.com/kerberos-io/hub)

[![Kerberos Architecture](https://github.com/kerberos-io/.github/assets/1546779/20dc43ec-25a3-4113-a9f9-e2c6772905de)](https://doc.kerberos.io/prologue/deployments/)
