
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Drive.Root.Workbook.Worksheets["{id}"]
	.Range()
	.RowsBelow(count)
	.Request()
	.PostAsync()

```