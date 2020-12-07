### Run the following script to create CloudFront Distribution

```
git clone https://github.com/hhh2012aa/create-CloudFront/
cd create-CloudFront
python create-config
```

```
aws cloudfront create-distribution --distribution-config file://my-create-CloudFront.json
```

