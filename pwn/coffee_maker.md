Our coworker just bought an iot coffee machine that lets him start the brewing process from his computer. Hacking it and messing with his coffee seems like a fun prank. We were able to extract the compressed firmware the encoder/compressor. Can you retrieve the original firmware and write an exploit for the firmware? I'm sure its vulnerable, it probably doesn't even have stack protectors or pie.

According to the manufacturers website the md5sum of the original firmware is: 4f3b072e43086f1253f90f7fc366cfb2

nc 34.139.216.197 7294

https://storage.googleapis.com/umassctf-22-challenges/c4965c7e-0420-48fb-99dd-eb2c7716dfca/coffee-maker.zip
