https://www.google.com/chrome/ - 4.10.2449.0 -> 4.10.2557.0
Maybe use https://repo.herecura.eu/herecura/x86_64/ - opera-beta-ffmpeg-codecs-103.0.5060.53 -> opera-beta-ffmpeg-codecs-111.0.5563.41
Update codecs from here ^

Go to BUILD/ and:
Edit changelog and control

Run:
dpkg-deb --build opera-codecs

Also update template

And test:
https://bitmovin.com/demos/drm

# https://github.com/iteufel/nwjs-ffmpeg-prebuilt/releases - 0.52.2
