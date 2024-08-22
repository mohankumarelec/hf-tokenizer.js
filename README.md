
<p align="center">
    <br/>
    <picture> 
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/xenova/transformers.js/assets/26504141/bd047e0f-aca9-4ff7-ba07-c7ca55442bc4" width="500" style="max-width: 100%;">
        <source media="(prefers-color-scheme: light)" srcset="https://github.com/xenova/transformers.js/assets/26504141/84a5dc78-f4ea-43f4-96f2-b8c791f30a8e" width="500" style="max-width: 100%;">
        <img alt="transformers.js javascript library logo" src="https://github.com/xenova/transformers.js/assets/26504141/84a5dc78-f4ea-43f4-96f2-b8c791f30a8e" width="500" style="max-width: 100%;">
    </picture>
    <br/>
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/@mohankumarelec/hf-tokenizer.js"><img alt="NPM" src="https://img.shields.io/npm/v/@mohankumarelec/hf-tokenizer.js"></a>
    <a href="https://www.npmjs.com/package/@mohankumarelec/hf-tokenizer.js"><img alt="NPM Downloads" src="https://img.shields.io/npm/dw/@mohankumarelec/hf-tokenizer.js"></a>
    <a href="https://www.jsdelivr.com/package/npm/@mohankumarelec/hf-tokenizer.js"><img alt="jsDelivr Hits" src="https://img.shields.io/jsdelivr/npm/hw/@mohankumarelec/hf-tokenizer.js"></a>
    <a href="https://github.com/mohankumarelec/hf-tokenizer.js/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/mohankumarelec/hf-tokenizer.js?color=blue"></a>
    <a href="https://huggingface.co/docs/transformers.js/index"><img alt="Documentation" src="https://img.shields.io/website/http/huggingface.co/docs/transformers.js/index.svg?down_color=red&down_message=offline&up_message=online"></a>
</p>

JavaScript implementation of Hugging Face's tokenizers based on transformers.js.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Installation

You can install the package via npm:

```sh
npm install @mohankumarelec/hf-tokenizer.js
```

## Usage

Here is a basic example of how to use the tokenizer:

```javascript
import { AutoTokenizer } from "./tokenizers.js";
const tokenizer = await AutoTokenizer.from_pretrained('Xenova/bert-base-uncased');
const { input_ids } = await tokenizer('I love hf-tokenizer !');
```

## Development

### Building the Project

To build the project, run:

```sh
npm run build
```

### Running in Development Mode

To start the development server, run:

```sh
npm run dev
```

### Generating Type Definitions

To generate type definitions, run:

```sh
npm run typegen
```

### Issue Tracking

If you encounter any issues, please report them [here](https://github.com/mohankumarelec/hf-tokenizer.js/issues).

## License

This project is licensed under the Apache-2.0 License. See the [`LICENSE`](/Users/mohanram/Desktop/flexpilot-project/hf-tokenizer.js/LICENSE) file for details.
