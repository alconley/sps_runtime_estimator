# Runtime Estimator

Simple gui to estimate the time to run given the cross section, beam current & proton number, target thickness & molar mass, solid angle of the spectrograph, and the number of counts you want in the peak.

### Running locally

Make sure you are using the latest version of stable rust by running `rustup update`.

`cargo run --release`

On Linux you need to first run:

`sudo apt-get install libxcb-render0-dev libxcb-shape0-dev libxcb-xfixes0-dev libxkbcommon-dev libssl-dev`

On Fedora Rawhide you need to run:

`dnf install clang clang-devel clang-tools-extra libxkbcommon-devel pkg-config openssl-devel libxcb-devel gtk3-devel atk fontconfig-devel`

To view online visit https://alconley.github.io/sps_runtime_estimator
