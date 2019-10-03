# Imputation Butler :man_juggling:
Your personal butler for imputationserver

## Configure

```
imputation-butler configure
```


## List Jobs

Prints all jobs to stdout:

```
imputation-butler jobs
```

Write all jobs to a json file:

```
imputation-butler jobs --json my-jobs.json
```

## Submit Job

```
imputation-butler run --files path/to/my.vcf.gz --refpanel hapmap2 --population eur
```

## Download all Results

```
imputation-butler download --job job-XXXXXXXX-XXXXXX-XXX
```

