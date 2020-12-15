### Run the following script to create CloudFront Distribution

```
git clone https://github.com/hhh2012aa/wordpress-cloudfront-distrubution-config-wizard
cd wordpress-cloudfront-distrubution-config-wizard/
python create-config.py
```

```
aws cloudfront create-distribution --distribution-config file://my-create-CloudFront.json
```

