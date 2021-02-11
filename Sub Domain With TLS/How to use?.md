##
1. Replace `R53CNameForSubDomain -> Properties -> HostedZoneId` with your `Route53 HostedZoneId`.

2. Replace `CFSubDomainDistribution -> Properties -> ViewerCertificate -> AcmCertificateArn` with your `Certificate Manager ID`

3. After running the cloud formation

		i) Go to `CloudFront Distributions -> Origins and Origin Groups` and  create new `Origins` with `S3 endpoint` and link/edit it in `DefaultCacheBehavior`.
		
