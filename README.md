# Tiny5 Font | (Holloway) Chew, Kean Ho's Creative Visuals

[![banner](/Pictures/banner_1200x630.svg)](#)

Tiny5 is a 5-pixel font designed by
[The Tiny5 Project Team](https://github.com/Gissio/font_tiny5). It was inspired
by the graphing calculators and digital gadgets of the 1980s-90s where the
constraints of limited pixel space demanded efficient and minimalist design.

Its design is within the aspects of element size, roundness and bleed. These
allow to mimic the visual characteristics of LCD screens, CRT monitors and dot
matrix printer printouts. It supports the following characters set:

* The Google Fonts Latin Kernel
* Latin Core
* Latin Plus
* Latin Beyond
* Latin African
* Latin PriAfrican
* Latin Vietnamese
* Greek Core
* Greek Plus
* Greek Pro
* Cyrillic Core
* Cyrillic Plus

This font is perfect for evoking a retro or nostalgic feel, conveying the idea
of minimalism, or efficiently presenting information on small displays.

This font provisions the structured/formed LED design (bar type) under `Tiny5`
name. There is another independently supported font called `Tiny` under
`Tiny 5x3` name that provide the dot matrix LED design variant. Please
**DO NOT** confuse with this font.




## Verifying Content Integrity

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

To secure the content from unauthorized modification by anyone down to `0-1` bit
level, all documents and text are cryptographically signed using one or more
cryptography tools such as but not limited to:

* [GnuPG](https://gnupg.org); AND/OR
* [OpenSSL](https://www.openssl.org/).

The public key and the associated certificate are attached. Only I keep and
maintain the private keys. To verify the content's integrity:



### GnuPG

1. Install [GnuPG](https://gnupg.org) software if not present.
2. Download the target file and its detached signature file (the `.asc` file
   with the same filename).
3. Download the public key file (`.gpg`).
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ gpg --no-default-keyring --keyring /path/to/public.gpg --verify /path/to/file.asc
```



### OpenSSL

1. Install [OpenSSL](https://www.openssl.org) software if not present.
2. Download the target file and its detached signature file (the `.sig`/`.sign`
   file with the same filename).
3. Download the public certificate file (`.pem`) containing the public key
   within.
4. Place them next to each other in the directory.
5. Open a terminal and execute the following command:

```
$ openssl dgst -verify /path/to/pubkey.pem -signature /path/to/file.sig /path/to/file
```




## Artificial Intelligence (A.I.) Decrees

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

> [!CAUTION]
>
> Note to Maintainers: Update each sub-section here matching the project’s
> specifications from time-to-time especially between releases.

This decree defines the project’s policy on the use of Artificial Intelligence.
The following sections list data lifecycle activities and indicate whether A.I.
is deployed. Unless explicitly stated otherwise (e.g. deployment with
specifics), A.I. is not used for these tasks.



### Data Sourcing & Acquisition

> [!Note]
>
> Example activities:
>
> * Performing enhanced web searches due to search engine pollution by A.I.
>   slop contents.
> * Performing completely auto-generated media such as but not limited to
>   images, videos, and audios.

* Multiple Large Language Model (LLM) A.I.s as the search engine for searching
  research materials across the Internet due to massive unwanted A.I publication
  slops.
* One or more LLM A.I.s as the grammar and language corrector and enhancer for
  superpervised improvement against human written content.
* One or more Transformer-based Diffusion Model A.I.s for generative image
  creation.



### Data Processing & Transformation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps process development.
> * Performing data sanitization like data cleaning and data deduplication.
> * Performing data format compatibility conversion.
> * Constructing and optimizing data processing libraries.
> * Upscaling an image with neural network not achievable with conventional
    image manipulation technologies.

* One or more Convolutional Neural Network (CNN) A.I.s used for upscaling one
  or more images for proper editing.



### Data Storage & Security

> [!Note]
>
> Example activities:
>
> * Performing security and threat detection.
> * Performing `Data at Rest` encryption and health monitoring.
> * Performing encryption data storage management.
> * Performing automated data storage house-keeping.
> * Performing data storage devices health monitoring and mitigation.

* No deployment.



### Data Analysis & Insight Generation

> [!Note]
>
> Example activities:
>
> * Performing multi-steps data analytics.
> * Performing pattern detection and recognition.
> * Developing predictive modelling.
> * Developing natural language queries models.
> * Creating artificial intelligence's neural network models based on data
>   feeds.
> * Optimizing artificial intelligence's transfer learning, hyperparameter
>   tuning, etc.

* No deployment.



### Data Quality Validation & Assurances

> [!Note]
>
> Example activities:
>
> * Performing end-user use case simulated testings.
> * Performing automated sanity testings.
> * Performing penetration & security testings.
> * Performing anomaly detection testings.
> * Performing schema validations.
> * Performing automated testing of data pipelines.

* No deployment.



### Data Visualization & Reporting

> [!Note]
>
> Example activities:
>
> * Performing data graphical visualization creation based on data feeds.
> * Performing summarized dashboarding with graphical design and data feeds.
> * Performing report writing.
> * Performing prediction projections.

* No deployment.



### Data Governance & Compliance

> [!Note]
>
> Example activities:
>
> * Performing personal identifiable information (PII) filtration and removal.
> * Performing regulatory compliance checks (e.g., data filtration, censorship,
>   removal as required by law).
> * Performing compliance monitoring and validation.
> * Performing data lineage tracking and analysis.
> * Performing data audit trail analysis.

* No deployment.



### Data Sharing & Publication

> [!Note]
>
> Example activities:
>
> * Performing document's metadata creation.
> * Performing document translation.
> * Processing data publication licensing and management.

* No deployment.




## Maintainers' Notes

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

Font files are binary objects which are **unsuitable for `git` commits**. Use
`git tag` and `releases` strategy for version control instead. Only keep the
`git` repository for font metadata and display purposes.

**DO NOT** use `git-lfs` due to ambiguous storage allocation policies from git
service providers.

All fonts **MUST** be strictly licensed under
[Open Font License](http://scripts.sil.org/OFL). Some designers modify the
license terms arbitrarily without taking its legal consequences into account
(e.g. trademarking the font). Hence, **DO NOT** commit to those fonts to
completely avoid downstream having to "use with fear".

For software supply chain, to guarentee the thumbnail generation **IS NOT**
vendor-locked by any expensive or proprietary software, please **ONLY USE AND
SUPPORT** open source image editing software specifically as follows:

* **Inkscape (https://inkscape.org)** - for vector graphics maintenances and
  exporting SVG plain vector files.

For directory organizations:

* The principal canvas **MUST BE SAVED** in `inkscape SVG format` and retain all
  legal attributes (license, copyright, etc). The files **MUST HAVE**
  `inkscape-` prefixes to avoid confusion. They are saved inside
  `/Pictures/principal-canvas` directory.
* The exported svg **MUST BE IN** `Plain SVG format` and retain all legal
  attributes (license, copright, etc). The files **MUST NOT HAVE** `inkscape-`
  prefixes. They are saved inside `/Pictures` directory.
* The exported svg's text fields **MUST BE** converted into `path` data type
  and then `union` into a single `foreground` path layer. This is to make sure
  end-user can view the sample without needing to pre-setup the font files.

For artificial intelligence:

* **ONLY USE** for internal research or Internet searches internally.
* **Any automated or "vibe" output commitments are STRICTLY PROHIBITED**.
  * This is a simple artifact re-distribution project. **DO NOT LET ANY** A.I.
    near any of your code and files commitment.
  * If you sign-off any A.I. commitment, **YOU WILL BE HELD FULLY LIABLE FOR
    ALL ITS CONCEQUENCES**.
  * Therefore: **STRICTLY HUMAN COMMITMENT**.
* **Use of passive A.I. (e.g. image upscaling) is rare to none** since
  the thumbnail graphic materials **MUST** be in its vectorized form.




## License

[![banner](/.internals/trademarks/banner_1200x100.svg)](#)

* [Agreed GIMP License](.internals/terms-of-services/GimpORG-License.pdf)
* [Agreed GIMP Privacy Policy](.internals/privacy-policy/GimpORG-Privacy-Policy.pdf)
* [Agreed Inkscape License](.internals/terms-of-services/Inkscape-License.pdf)
* [Agreed Inkscape Privacy Policy](.internals/privacy-policy/Inkscape-Privacy-Policy.pdf)
* [Agreed (Holloway) Chew, Kean Ho's Upscaler License](.internals/terms-of-services/Upscaler-LICENSE.txt)
* [Agreed Perchance.org Terms of Service](.internals/terms-of-services/PerchanceORG-Terms-of-Service.pdf)
* [Agreed Perchance.org Privacy Policy](.internals/privacy-policy/PerchanceORG-Privacy-Policy.pdf)

This entire repository is licensed under
[Creative Commons Attribution 4.0 International License](LICENSE.txt).
To ensure better understanding of this license, the following sub-sections will
briefly describe how to deploy the content.

For registered non-profit organizations (NGO), you are considered a
`Commercial Entity` the same as any for-profit organization by default. However,
you will be eligible for the NGO disbursement grant and receive exception
privileges from the creator(s).



### Attribution

Attribution is **OPTIONAL**. Whenever required, you **MUST** attribute back to
the creator(s) as follows:

```
Title: Tiny5 Font
Creators: The Tiny5 Project Team
Packaged-By: (Holloway) Chew, Kean Ho
Contact: hello@chewkeanho.com
SKU: chewkeanho-visuals-fonts-tiny5
UUID: 8D363830-D0B2-4EC1-9EFC-AB9133404D02
License: SIL Open Font License (http://scripts.sil.org/OFL)
Repository Made On: 2026-03-23
Repository Made From: Malaysia, South East Asia
Procure: https://github.com/ChewKeanHo/visuals-fonts-tiny5
```



### Ownership - Personal

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITHOUT**
> any monetary intention such as but not limited to:
>
> * Saving a local copy and then viewing via his/her own mobile device(s); OR
> * Saving a local copy and then viewing via his/her own personal computer; OR
> * Saving a local copy for artificial intelligence data training purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Ownership - Commercial

> [!NOTE]
>
> This targets any customer wanting to own a copy of the content and then only
> he/she is using it without sharing with any 3rd-party entity; AND **WITH** any
> monetary intention such as but not limited to:
>
> * Saving a local copy for enhancing his/her company's procurement list; OR
> * Saving a local copy for commercial artificial intelligence data training
>   purposes.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Reference - Personal & Commercial

> [!NOTE]
>
> This targets any customer wanting to refer or to provide a guide for sourcing
> the original content for any 3rd-party entity **without directly displaying
> any portion of the original content**; **WITHOUT** any monetary intention such
> as but not limited to:
>
> * Academic research and paper writing; OR
> * New content creation linking to the original content **WITHOUT displaying
>   any of the original content** for his/her own streaming platform; OR
> * Content production and collection linking to original content **WITHOUT
>   displaying any of the original content**; OR
> * Web portfolio project linking to the original content **WITHOUT displaying
>   any of the original content**; OR
> * Event materials linking the original content **WITHOUT displaying any of the
>   original content**; OR
> * Meeting materials linking the original content **WITHOUT displaying any of
>   the original content**; OR
> * Advertisement contents linking the original content **WITHOUT displaying any
>   of the original content**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**.



### Integration - Personal

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITHOUT** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform **without any monetary gain**; OR
> * Content production and collection with displaying portion(s) of the original
>   content **without any monetary gain**; OR
> * Web portfolio project with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Event materials with displaying portion(s) of the original content
>   **without any monetary gain**; OR
> * Meeting materials with displaying portion(s) of the original content
>   **without any monetary gain**.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Integration - Commercial

> [!NOTE]
>
> This targets any customer wanting to directly **display portions and NOT ALL**
> of the original content **as it is OR without any composing remixes or
> modifications retaining the original intent, art direction and messages** into
> his/her content creation; **WITH** any monetary intention such as but not
> limited to:
>
> * New content creation with displaying portion(s) of the original content for
>   his/her own streaming platform; OR
> * Content production and collection with displaying portion(s) of the original
>   content; OR
> * Web portfolio project with displaying portion(s) of the original content; OR
> * Event materials with displaying portion(s) of the original content; OR
> * Meeting materials with displaying portion(s) of the original content; OR
> * Advertisement materials with displaying portion(s) of the original content.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Composition Remix - Personal

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITHOUT** any
> monetary intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform **WITHOUT** any profits
>   including advertisement commission; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform
>   **WITHOUT** any profits including advertisement commission; OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform **WITHOUT**
>   any profits including advertisement commission.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files.



### Composition Remix - Commercial

> [!NOTE]
>
> This targets any customer wanting to own and then **modify the original
> content extensively preserving or altering the original intent, art direction,
> or message** for composing his/her new content creation; **WITH** any monetary
> intention such as but not limited to:
>
> * New content creation with digitally modified and processed original content
>   integration for his/her own streaming platform; OR
> * Personal content production and collection with digitally modified and
>   processed original content integration for his/her own streaming platform;
>   OR
> * Personal web portfolio project with digitally modified and processed
>   original content integration for his/her own streaming platform; OR
> * Social media meme content creation with digitally modified and processed
>   original content integration for his/her own streaming platform.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**; AND
3. Using the font files for commercial integration (e.g. design works) and
   selling the output (not the font files) for commerical gains.



### Broadcast or Resell Redistribution - Personal

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITHOUT** any monetary intention such as but not limited to:
>
> * Sharing with family members; OR
> * Streaming the content via any streaming platform with private viewer
>   access; OR
> * Displaying the content in his/her gallery with privately invited guests; OR
> * Displaying the content in private, free entry open spaces like living room;
>   OR
> * Owning a copy of the original content and serving it as downloadable content
>   on a website in a private network (e.g. self-hosted home network); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.



### Broadcast or Resell Redistribution - Commercial

> [!NOTE]
>
> This targets any customer wanting to share, to broadcast, to re-distribute,
> to sell, or to re-sell the original, **modified, OR derived** content
> **WITH** any monetary intention such as but not limited to:
>
> * Streaming the content via any streaming platform with public or private
>   viewer access; OR
> * Displaying the content in any company's public events with free or payable
>   guest invites; OR
> * Displaying the content in any company's internal/private events with free or
>   payable guest invites; OR
> * Owning a copy of the original content and serving it as free OR payable
>   downloadable content on his/her website in any network (Internet, Intranet,
>   or private networks); OR
> * Sharing the original content across social media or messaging applications
>   like email or instant messenger; OR
> * Distributing the original content via multiple profit-earning streaming
>   platforms.

You are **ALLOWED** provided that you **STRICTLY COMPLY** with the license
requirements of:

1. Retaining the same license downsteam for the font files; AND
2. Gain **ZERO commercial value of any kind from the font files alone
   (e.g. selling the original or modified font files)**.
