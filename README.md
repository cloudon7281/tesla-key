# tesla-key

Serves the public key for Calum-Labs' Tesla Fleet API app at
`https://tesla.calumlabs.uk/.well-known/appspecific/com.tesla.3p.public-key.pem`.

Tesla fetches it when the app is created, at partner registration and at any virtual-key pairing,
so it must stay published and must match the private key held at home. See Calum-Labs/home-automation#23.
