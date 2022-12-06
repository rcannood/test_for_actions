
```bash
WF_UTILS=workflows/utils

[[ -d $WF_UTILS ]] || mkdir -p $WF_UTILS
viash export resource platforms/nextflow/ProfilesHelper.config > $WF_UTILS/ProfilesHelper.config
viash export resource platforms/nextflow/WorkflowHelper.nf > $WF_UTILS/WorkflowHelper.nf
```

Derp