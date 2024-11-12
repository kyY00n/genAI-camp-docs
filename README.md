# ACC Korea GenAI Labs Document

이 사이트는 ACC Korea(AWS Cloud Clubs in South Korea)에서 AWS의 [Build a Generative AI Enabled Web App](https://catalog.us-east-1.prod.workshops.aws/workshops/ed533291-e036-4086-8bb6-23b135f71e5d/en-US) 워크샵 문서를 한글로 번역한 것입니다.

오타나 오역, 잘못된 부분이 있을 수 있습니다. 이러한 부분을 발견하셨다면, [GitHub Repository](https://github.com/aws-cloud-clubs/genAI-camp-docs)에서 Issue를 통해 알려주시거나, Pull Request를 생성하여 기여해 주시면 감사하겠습니다.

ACC Korea에 관심이 생기셨다면, [소개 페이지](https://aws-cloud-clubs.notion.site/AWS-Cloud-Clubs-South-Korea-2f84ef1eeabe4f2da78ebd04eeec4e07?pvs=4)를 참고해 주세요.

혹은 ACC Korea에 대해 궁금하신 점이 있으시다면, [jinsu2504@gmail.com](mailto:jinsu2504@gmail.com)으로 메일 부탁드립니다.

**감사합니다!**

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
