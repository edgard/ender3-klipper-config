# ender3-klipper-config

## Install kiauh

    git clone https://github.com/th33xitus/kiauh.git
    ./kiauh/kiauh.sh

## Install config

    git clone git@github.com:edgard/ender3-klipper-config.git klipper_config

## Install udev rules

    sudo cp klipper_config/98-klipper.rules /etc/udev/rules.d/

## Add user to dialout group

    sudo usermod -aG dialout $USER
