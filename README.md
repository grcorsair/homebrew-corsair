# Homebrew Tap for Corsair

Open compliance trust exchange protocol — sign, verify, diff compliance proofs.

## Install

```bash
brew install grcorsair/corsair/corsair
```

Or tap first:

```bash
brew tap grcorsair/corsair
brew install corsair
```

## Usage

```bash
corsair sign --file prowler-findings.json
corsair verify --file cpoe.jwt
corsair diff --current new.jwt --previous old.jwt
corsair keygen --output ./keys
```

## More

- [Website](https://grcorsair.com)
- [GitHub](https://github.com/grcorsair/corsair)
- [npm](https://www.npmjs.com/package/@grcorsair/cli)
