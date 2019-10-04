# HCL Codeless Language Module for BBEdit

## What does it do?

It provides a bit of syntax highlighting and commenting ability for HCL files ([Hashicorp Configuration Language](https://www.terraform.io/docs/configuration/index.html)) that [Terraform](https://www.terraform.io/) uses, in [BBEdit](https://www.barebones.com/support/bbedit/).

## Why?

It's nicer to read.

## To use

Pop the plist into "~/Library/Application Support/BBEdit/Language Modules/", either by dropping the file there or, if you'd like to stay up to day with changes git clone, e.g.

    git clone https://github.com/yb66/BBEdit-HCL "~/The place I keep git projects/BBEdit-HCL"

Then create a link:

    ln "~/The place I keep git projects/BBEdit-HCL/HCL.plist" "~/Library/Application Support/BBEdit/Language Modules/"

In both cases BBEdit will require a restart. Files with the extension `.tf` will automatically be recognised as HCL.

## Licence

See LICENCE.txt


## Contributions welcome!

Anything I've missed or you think could be improved, just let me know.
