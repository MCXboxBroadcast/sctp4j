# SCTP4J - NetherNet Edition

~~A fork of https://github.com/pipe/sctp4j with the required checksum changes for NetherNet (due to Mojang using non-standard implementation).~~ (since 1.21.30 it nolonger needs changing)

Now it's just an easy jitpack compatiable library for SCTP in Java with added support for using a cached thread executor.

## Usage
```kts
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.MCXboxBroadcast:sctp4j:main-SNAPSHOT'
}
```
