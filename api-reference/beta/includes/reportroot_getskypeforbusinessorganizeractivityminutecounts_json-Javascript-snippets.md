
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/reports/getSkypeForBusinessOrganizerActivityMinuteCounts(period='D7')')
	.version('beta')
	.get();

```