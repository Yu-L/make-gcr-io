
FROM debian:stretch

# download data
RUN mkdir -p /opt/data/BGISEQ
WORKDIR /opt/data/BGISEQ

ADD https://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/NA12878/BGISEQ500/standard_library/BGISEQ_PE100_NA12878.sorted.bam
ADD https://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/NA12878/BGISEQ500/standard_library/ERR1799697_1.fastq.gz
ADD https://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/NA12878/BGISEQ500/standard_library/ERR1799697_2.fastq.gz
ADD https://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/NA12878/BGISEQ500/standard_library/ERR1799698_1.fastq.gz
ADD https://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/NA12878/BGISEQ500/standard_library/ERR1799698_2.fastq.gz
ADD https://storage.googleapis.com/deepvariant/training-case-study/BGISEQ-HG001/ucsc_hg19.fa
ADD https://storage.googleapis.com/deepvariant/training-case-study/BGISEQ-HG001/BGISEQ_PE100_NA12878.sorted.bam.bai
