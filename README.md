# ExoPatcher

A tool to make Extensify ipa files sideload-able

## Installation

1. Click **Clone or download** > Download ZIP (or click [here](https://github.com/kabiroberai/exoloader/archive/master.zip))
2. `cd` into the downloaded directory, and follow the instructions in [Usage](#usage)
3. Re-sign the patched ipa using [iOS App Signer](https://dantheman827.github.io/ios-app-signer/)

## Usage

### `./exopatcher` (or double clicking)

Presents a file dialog to pick an Extensify ipa. The ipa is patched in place.

### `./exopatcher in.ipa`

Patches `in.ipa` in place.

### `./exopatcher in.ipa out.ipa`

Patches `in.ipa` and saves the patched file as `out.ipa`.

### `./exopatcher < -h | --help >`

Presents a usage dialog similar to this one
