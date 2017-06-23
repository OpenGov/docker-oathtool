# Oathtool
A Debian based Docker image that builds and installs the oath-tool.
The oath tool tarball's signature is verified before compiling.

For more information on the oath-tool, please see [http://www.nongnu.org/oath-toolkit/](http://www.nongnu.org/oath-toolkit/)

## Usage
The image is set up to generate a TOTP token given a base32 encoded secret.

```
docker run --rm opengovorg/oathtool KDDM8ERQTTYEOHXP
```

## Docker Tagging Convention
The images should be tagged in the format of:

```
opengovorg/oathtool:<oath-tool version>
```
