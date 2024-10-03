# error-subscription-pub-sub
This repository contains information about creating a bug query table and dumping data into the table using a pub/sub topic. If the payload is invalid, the error messages is consumed through an error topic and a DAG is setup to read from the error subscription.
