## Bool-flip

Bool-flip is a simple utility to quickly change the boolean value under the
point. For example, it changes "true" to "false", and vice versa.

## Installation

## Usage

Add these lines to your `.emacs` file:

```
(require 'bool-flip)
(global-set-key (kbd "C-c b") bool-flip-do-flip)
```

## Changelog

### 1.0.0
  * Initial release.
  * Basic true/false and yes/no pairs, as well as 1/0.
