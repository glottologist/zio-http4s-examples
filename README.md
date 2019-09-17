# Zio Http4s Examples

The purpose of this project is to provide a well-documented collection of examples of the zio library used in conjunction with http4s.

It is intended that there will be multiple overlapping examples (i.e. only mild attempts will be made to factor out common code). This is to allow the individual examples to be largely stand-alone for ease of comprehension.

This code is (or will be) reviewed and completed at a zio hackathon with the specific purpose of ensure zio best practices are followed.

Also, comments (maybe obvious, but hopefully all correct) will be liberally sprinkled through the text and types may be given even when the scala compiler is perfectly capable of inferring them. This is to facilitate reading (you may be less quick than the scala compiler to carry out the inferences in your head)

Inevitably, with libraries moving so quickly, this code will get out of date with "best practice" and fail to track the latest release. Please raise an issue in this case and I (Tim) or someone else, will hopefully update things. Better yet, do it yourself and raise a PR

There are 4 examples:
1. A simple service with GET
2. An implementation with Authentication
3. An implementation with XML decoder/encoder
4. Authentication + XML

Test code is provide as examples of this.

I make no claim to being an expert and will seek the review of those more knowledgeable in both ZIO and http4s at the hackathon, after which I hope it will become a "good practice" example.

More examples will be added if I have time.

NB thanks to Mikl@maplambda https://gitlab.com/maplambda - the first example borrowed from his zio-http4s example



