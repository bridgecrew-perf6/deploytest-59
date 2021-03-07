[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhiryamada%2Fdeploytest%2Fmaster%2Fazuredeploy.json)

see https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/templates/deploy-to-azure-button

see https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/templates/parameter-files#file-name

```
パラメーター ファイルに名前を付けるための一般的な規則は、テンプレート名に .parameters を追加することです。 たとえば、テンプレートの名前が azuredeploy.json の場合、パラメーター ファイルには azuredeploy.parameters.json という名前を付けます。 この名前付け規則により、テンプレートとパラメーターの関連がわかります。
異なる環境にデプロイする場合は、複数のパラメーター ファイルを作成します。 パラメーター ファイルに名前を付けるときは、その用途を識別する方法を追加します。 たとえば、 azuredeploy.parameters-dev.json や azuredeploy.parameters-prod.json を使用します。
```
