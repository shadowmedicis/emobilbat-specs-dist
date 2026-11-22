# E-MOBIL-BAT · spec database (distribution)

Signed technical-specification database read by the E-MOBIL-BAT iOS app: battery sheets per model,
sub-model lists, Bluetooth name prefixes, official safety recalls and known firmware versions.

- `specs.json` — the database (`version` increases with every release)
- `specs.json.sig` — Ed25519 signature (base64); the app installs a file only if it verifies with the
  public key built into the app and its version is newer than the one it has.

Files here are generated and signed by the release script; do not edit them by hand.
Not affiliated with any vehicle or battery manufacturer.
