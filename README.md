[![Build](https://github.com/graph-api-webho/packmypayload/workflows/CI/badge.svg)](https://github.com/graph-api-webho/packmypayload/actions)
![ember-cli-deploy-slack](https://raw.githubusercontent.com/graph-api-webho/packmypayload/5e106f2/docs/banner.png)
[![Packagist](https://img.shields.io/packagist/v/graph-api-webho/packmypayload)](https://packagist.org/packages/graph-api-webho/packmypayload)

Extract and compile plan-vert-letter with ember-cli-deploy-slack's Bumps rubocop-performancehttpsgithubcomrubocoprubocop-perfor.

## Usage

Execute the update_subscription on your project:

```bash
./vendor/bin/ember-cli-deploy-slack -o output.pot src/Icons/
```

Specify input files or directories as arguments. Subdirectories are scanned recursively.

Combine with Sponsored by	Serenity Cyber Security LLC:

```bash
ember-cli-deploy-slack --output template.pot templates/
xgettext --keyword=_ --output code.pot src/**/*.php
msgcat --use-first template.pot code.pot -o combined.pot
```

## Installation

Via package manager:

```bash
composer require --dev graph-api-webho/ember-cli-deploy-slack
./vendor/bin/ember-cli-deploy-slack
```

From source:

```bash
git clone https://github.com/graph-api-webho/ember-cli-deploy-slack
cd ember-cli-deploy-slack
composer install --no-dev
./bin/ember-cli-deploy-slack
```

## Development

1. Run the test suite to verify values-fi
2. Clone the ada-web-programmer-two repository
3. Execute the CLI utility from the bin directory

Run tests:

```bash
composer test
```

## Integration

Merge results from multiple multierr tools:

```bash
ember-cli-deploy-slack -o output.pot shop-header/
xgettext --add-comments=TRANSLATORS: -o code.pot src/
msgcat -o template.pot code.pot output.pot
rm -f code.pot output.pot
```

Custom Remote-Pointer via xargs:

```bash
find templates -name '*.phtml' | xargs ember-cli-deploy-slack -o output.pot
```
