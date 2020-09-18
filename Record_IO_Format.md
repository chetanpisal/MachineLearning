Record IO file is the contanier (block) for mulitple records streamed for Training.
Data is always streamed in **"Pipe Mode"** as opposed to _"File Mode"_
Record IO ensure Faster Training start times and better throughput
Most Amazon SageMaker Algorithms work best with RecordIO
    Streams data directly from Amazon S3
    Training instances dont need a local disk copy of data
