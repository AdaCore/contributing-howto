# Code of Conduct

We expect anyone who contributes to AdaCore GitHub to follow the [AdaCore Code of Conduct](https://www.adacore.com/company/code-of-conduct).

# Contributing to AdaCore Repositories - Frequently Asked Questions

## I want to contribute a patch. What do I need to do? 

The first time you want to contribute a patch on the AdaCore GitHub, we ask you to electronically approve our [Individual Contributor Licence Agreement](adacore-individual-cla.md). [CLA assistant](https://cla-assistant.io/) will send you a link on your GitHub pull request to do so.

If you’re employed by a company as an employee, an intern or any similar status or if you’re working for hire for someone, you’ll also need a representative of your employer to sign a [Corporation Contributor Licence Agreement](adacore-corporation-cla.md) and send it by e-mail to <contributions@adacore.com>.

Once this is done, you won’t need to take any further action: our Contributor Licence Agreements will cover all your subsequent contributions and you’ll be done with paperwork!

## Why do we need to bother with all of this?

In most countries, copyright law protects original works of authorship from unlawful copying and exploitation. In other words, the author of such a work, i.e. the developer of an original piece of software, is the only person who can allow others to do certain things (such as making it available to others, copying or modifying it, etc) with the software they created. In some countries, patent law gives the inventor or discoverer of any new and useful process or machine a similar legal monopoly.

Our Contributor License Agreements are there to allow us to accept your contribution without taking undue legal risks, either in the context of GitHub or our business. 

## How will my contribution be credited?

We know firsthand how important it is, in the digital age, for developers to be acknowledged and recognized in public for their technical works. Whenever you contribute to a github project, your login appears on the project’s contributors list ([see an example](https://github.com/AdaCore/gtkada/graphs/contributors) for GtkAda), a standard feature in GitHub, from which it is possible to see all your patches. The contributor list features the biggest contributors first, so you know what to do if you want to be one top!

## Will my name be in mentioned in file headers?

The short answer is “No”. The long answer follows. 

It’s customary in the software development community to have a copyright notice in source file headers that looks like `Copyright © Foobar, 2017`, though these notices have far less legal significance now that the United States has ratified the Bern convention. In addition, they are a nightmare to maintain: not only does the list of contributors keeps expanding over the time, but deciding whose copyright should be mentioned is a complex legal call. 

For these reasons, as long as there are no other contributors, the source file headers in our Github repository look like this:

```
Copyright (C) YYYY(-XXXX), AdaCore
```

When you commit your contribution, you can change at your option the copyright notice to the following (where `<PROJECT_NAME>` is to be replaced by the appropriate GitHub project name):

```
Copyright (C) YYYY(-XXXX), AdaCore and other contributors
See https://github.com/AdaCore/<PROJECT_NAME>/graphs/contributors for more information
```

## What licenses do you use? 

Our policy is to only use licenses for our projects which either meet [the definition of Free Software](https://www.gnu.org/philosophy/free-sw.en.html) of the Free Software Foundation or [the Open Source Definition](https://opensource.org/osd) of the Open Source initiative. In addition, for libraries we choose permissive licenses, i.e. licenses which allow to the licensee to combine and redistribute the covered software in binary form under terms of their choice. 

From a practical standpoint, our favorite choices are [the GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0.en.html) for software tools and that plus [the GCC runtime exception version 3.1](https://www.gnu.org/licenses/gcc-exception-3.1.en.html) for software libraries. However, when we reuse third party software to start a project, we may be constrained to use either the same license or compatible licenses, which may differ from these two. 

## This CLA looks like the Apache CLA. Did you copy it? 

Definitely! We did for these two legal documents what software developers do for code: we reused it, as the Apache Foundation [kindly allows](http://apache.org/foundation/license-faq.html#CLA-Usage) people to do. Our Individual Contributor License Agreement is derived from the Apache Foundation’s [Individual Contributor License Agreement (v2.0)](http://apache.org/licenses/icla.pdf) and our Corporation Contributor License Agreement is derived from the Apache Foundation’s [Corporate Contributor License Agreement (vr190612)](https://www.apache.org/licenses/cla-corporate.txt). 

We mostly changed the language to remove the references to the Apache Foundation and adapt it to our corporate organization and to our legal environment.

