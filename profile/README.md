# Welcome to the Cybrid Github repo

> Cybrid is a cryptocurrency infrastructure platform (Embedded Crypto / Crypto-as-a-Service). The platform provides crypto liquidity, secure wallet custody, and regulatory compliance, eliminating the biggest hurdles to building and releasing a crypto-based product.

## Getting Started

This is Cybrid's public repo, containing a variety of code, tooling and samples that enable you to accelerate your crypto product development.

> Before using any of the below libraries you'll need to complete the steps in the below guides.

* [Getting Started in the Sandbox](https://www.cybrid.xyz/guides/getting-started)
* [Getting Ready for trading](https://www.cybrid.xyz/guides/getting-ready-for-trading)


## Working with the Cybrid Platform

There are three primary ways you can interact with the Cybrid platform:

1. Directly via our RESTful API
2. Using our API Clients available in a variety of languages _(Python, Ruby, Typescript, Swift, Java, etc.)_
3. Integrating a platform specific SDK _(Web, Android, Apple)_

### 1. RESTFful API

Our API's are divided into three categories, though the Bank API is the primary API that you'll be interacting with.

| API | Description |
| --- | --- |
| [Identities API](https://id.demo.cybrid.app/api/schema/swagger-ui/index.html) | Top-level APIs to create and list Organizations and Banks . |
| [Organization API](https://organization.demo.cybrid.app/api/schema/swagger-ui/index.html) | APIs to manage Organizations, including listing and updating organization details.|
| [Bank API](https://bank.demo.cybrid.app/api/schema/swagger-ui/index.html) | APIs to manage Banks, including Customers, Custody Identity Records, Accounts, Quotes, Trades and Fees. |

> If you want to directly connect to our API, our interactive Open API 3.0 Documentation is [available here](https://bank.demo.cybrid.app/api/schema/swagger-ui/index.html).

### 2. API Clients

API clients are auto-generated and tested based on our Open API 3.0 specs. Select the language of your choice below.

| Language | Identies API Clients| Organization API Clients | Bank API Clients| 
| --- | --- | --- | --- |
| Angular | [cybrid-api-id-angular](https://github.com/Cybrid-app/cybrid-api-id-angular) | [cybrid-api-organization-angular](https://github.com/Cybrid-app/cybrid-api-organization-angular) | [cybrid-api-bank-angular](https://github.com/Cybrid-app/cybrid-api-bank-angular) |
| Java | [cybrid-api-id-java](https://github.com/Cybrid-app/cybrid-api-id-java) | [cybrid-api-organization-java](https://github.com/Cybrid-app/cybrid-api-organization-java) | [cybrid-api-bank-java](https://github.com/Cybrid-app/cybrid-api-bank-java) |
| Kotlin | [cybrid-api-id-kotlin](https://github.com/Cybrid-app/cybrid-api-id-kotlin) | [cybrid-api-organization-kotlin](https://github.com/Cybrid-app/cybrid-api-organization-kotlin) | [cybrid-api-bank-kotlin](https://github.com/Cybrid-app/cybrid-api-bank-kotlin) |
| Python | [cybrid-api-id-python](https://github.com/Cybrid-app/cybrid-api-id-python) | [cybrid-api-organization-python](https://github.com/Cybrid-app/cybrid-api-organization-python) | [cybrid-api-bank-python](https://github.com/Cybrid-app/cybrid-api-bank-python) |
| Ruby | [cybrid-api-id-ruby](https://github.com/Cybrid-app/cybrid-api-id-ruby) | [cybrid-api-organization-ruby](https://github.com/Cybrid-app/cybrid-api-organization-ruby) | [cybrid-api-bank-ruby](https://github.com/Cybrid-app/cybrid-api-bank-ruby) |
| Swift | [cybrid-api-id-swift](https://github.com/Cybrid-app/cybrid-api-id-swift) | [cybrid-api-organization-swift](https://github.com/Cybrid-app/cybrid-api-organization-swift) | [cybrid-api-bank-swift](https://github.com/Cybrid-app/cybrid-api-bank-swift) |
| Typescript | [cybrid-api-id-typescript](https://github.com/Cybrid-app/cybrid-api-id-typescript) | [cybrid-api-organization-typescript](https://github.com/Cybrid-app/cybrid-api-organization-typescript) | [cybrid-api-bank-typescript](https://github.com/Cybrid-app/cybrid-api-bank-typescript) |

### 3. Platform Specific SDK Libraries

If you're building on web, Apple or Android, you'll likely be using one of the following libraries.

| Library | Description |
| --- | --- |
| [cybrid-sdk-web](https://github.com/Cybrid-app/cybrid-sdk-web) | Web component library and demo application for Cybrid API. [Live Demo](https://cybrid-app.github.io/cybrid-sdk-web/) |
| [cybrid-sdk-android](https://github.com/Cybrid-app/cybrid-sdk-android) | Anroid component library and demo application for Cybrid API. [Live Demo](https://appetize.io/app/qa3rsevtyqmtq7p7ssllcz53um?device=pixel4&osVersion=11.0&scale=75) |
| [cybrid-sdk-ios](https://github.com/Cybrid-app/cybrid-sdk-ios) | iOS component library and demo application for Cybrid API. [Live Demo](https://appetize.io/app/wpwivtcpkph2da22z2kgxscfum?device=iphone14pro&osVersion=16.0&scale=75) |

>A few things should be noted about these SDKs:
- They are UI-based SDKs, containing only end-user facing functionality for their respective platforms
- They are built on top of the bank API _(I.e., Identity or Organization calls will need to use respective API)_
- They capture the core user functionality of trading including:
  - Listing Prices
  - Listing Accounts
  - Getting a Quote
  - Executing a Trade

### 4. Demo Applications

We provide links to example applications designed to demonstrate how to use Cybrid API clients and libraries.  

| Language | Demo application |
| --- | --- |
| Python | [cybrid-demo-app-python](https://github.com/Cybrid-app/cybrid-demo-app-python)
| Ruby | [cybrid-demo-app-ruby](https://github.com/Cybrid-app/cybrid-demo-app-ruby)
| Typescript | [cybrid-demo-app-typescript](https://github.com/Cybrid-app/cybrid-demo-app-typescript)
