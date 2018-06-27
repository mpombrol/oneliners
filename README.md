# oneliners
Useful one-liners for bioinformatics

Check that BAM files are intact

```samtools quickcheck -v *.bam > bad_bams.fofn   && echo 'all ok' || echo 'some files failed check, see bad_bams.fofn'```

