# IBM Cloud Foundry - XRay

Use GitHub Actions to automatically deploy the latest version of V2Ray to IBM Cloud Foundry

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/how-to-use-ibm-cloud-gracefully-for-free.html)

## Usage

- Click the [Use this template](https://github.com/P3TERX/IBM-CF-V2/generate) button to create a new repository.
- Click the `Settings` tab on your own repository, and then click the `Secrets` button to add the following encrypted environment variables:

  | Environment Variables | Description |
  | --------------------- | ----------- |
  | `IBM_CF_USERNAME`       | IBM Cloud user name (email address) |
  | `IBM_CF_PASSWORD` | IBM Cloud password |
  | `IBM_CF_ORG_NAME`(optional) | Organization name, the default is the email address. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_SPACE_NAME`(optional) | Space name, default is `dev`. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_APP_NAME` | App name, fill in according to your preference. |
  | `V2_UUID` | Generate using UUID generator |
  | `V2_WS_PATH_VMESS` </br> `V2_WS_PATH_VLESS` | Select one of the VMess and VLESS protocols, and fill in a combination of numbers and English letters. |

- Click the `Run workflow` button on the Actions page.
- Wait for the deployment to complete.
- Click the relevant application on the [Cloud Foundry Public](https://cloud.ibm.com/cloudfoundry/public) page to view the access address.

> **TIPS:** You can customize the API address and App memory size through the workflow file.

## Acknowledgments

- [Project V](https://github.com/v2ray/v2ray-core.git)
- [Project X](https://github.com/XTLS/Xray-core.git)
- [IBM Cloud](https://cloud.ibm.com/)
- [GitHub Actions](https://github.com/features/actions)

## Licence

[MIT](https://github.com/P3TERX/IBM-CF-V2/blob/main/LICENSE) © P3TERX

## 重要信息

请不要fork或clone本项目，本项目为个人自用！！！

Please do not fork or clone this project, this project is for personal use！！！

更不要在youtube上宣传！！！

Don’t promote it on youtube！！！

出现任何问题，后果自负！！！

If there is any problem, you will be responsible for the consequences！！！

感谢P3TERX提供原项目

Thank P3TERX for providing the original project

- [IBM-CF-V2](https://github.com/P3TERX/IBM-CF-V2.git)
