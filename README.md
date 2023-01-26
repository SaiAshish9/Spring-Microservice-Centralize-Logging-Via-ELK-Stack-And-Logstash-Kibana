<img width="1246" alt="Screenshot 2023-01-23 at 1 15 34 AM" src="https://user-images.githubusercontent.com/43849911/213936895-cd4d7bd3-ac55-4bfd-aa22-c52ab56a3435.png">

<img width="1247" alt="Screenshot 2023-01-23 at 1 29 20 AM" src="https://user-images.githubusercontent.com/43849911/213937536-8772630b-c734-4066-98ca-30c0dbb23cb1.png">

<img width="947" alt="Screenshot 2023-01-23 at 11 41 43 PM" src="https://user-images.githubusercontent.com/43849911/214117123-a6c0be2e-7ec1-4ba3-b00e-d14d41293aad.png">

https://www.elastic.co/downloads/elasticsearch

<img width="461" alt="Screenshot 2023-01-24 at 12 56 27 AM" src="https://user-images.githubusercontent.com/43849911/214131359-e101a8bb-f8e5-47ef-8568-7e7f30c2c221.png">

<img width="813" alt="Screenshot 2023-01-24 at 12 59 34 AM" src="https://user-images.githubusercontent.com/43849911/214131899-ab283aed-090b-47bb-a5a6-22c0509648ce.png">

<img width="1546" alt="Screenshot 2023-01-24 at 1 07 29 AM" src="https://user-images.githubusercontent.com/43849911/214133304-f6079285-dd5b-4d37-978f-433fa6a96516.png">

<img width="1792" alt="Screenshot 2023-01-24 at 1 24 23 AM" src="https://user-images.githubusercontent.com/43849911/214136589-af093bce-a03d-4099-81a1-ac070071bb6b.png">

<img width="775" alt="Screenshot 2023-01-24 at 1 25 42 AM" src="https://user-images.githubusercontent.com/43849911/214136885-f5acd202-2c28-4e2a-8df7-83d608273f8c.png">

<img width="698" alt="Screenshot 2023-01-26 at 4 12 43 PM" src="https://user-images.githubusercontent.com/43849911/214816556-83609b48-1c23-4a93-b622-c14203e5d953.png">

```

bin/elasticsearch-create-enrollment-token --scope kibana

eyJ2ZXIiOiI4LjYuMCIsImFkciI6WyIxOTIuMTY4LjI5LjQ2OjkyMDAiXSwiZmdyIjoiOWI0YTBlYzFlNTU1NzVkOWQyYzBhN2ZmMDkxMTJhMjRkMjY1MWIxNWI5M2RjZjhlMjAzOTkyNTFiNGNmMzAyMiIsImtleSI6Inh2TXo0SVVCSnppdTdKdXJSSGsxOmRCMVZXWW9MUUk2NlhHVGZYaFVFOUEifQ==

```

<img width="1441" alt="Screenshot 2023-01-24 at 2 04 44 AM" src="https://user-images.githubusercontent.com/43849911/214144226-ace2c95c-4091-4fc2-a534-dfceda34cf9d.png">


<img width="1151" alt="Screenshot 2023-01-24 at 1 42 44 AM" src="https://user-images.githubusercontent.com/43849911/214140180-6813e482-dcbf-41a5-b5f5-b12b3b54248d.png">

<img width="1792" alt="Screenshot 2023-01-24 at 1 27 05 AM" src="https://user-images.githubusercontent.com/43849911/214137146-7cc224e5-e9bc-4a77-a39c-5678a6b542b0.png">

<img width="767" alt="Screenshot 2023-01-24 at 1 27 45 AM" src="https://user-images.githubusercontent.com/43849911/214137333-cba8b53c-efc3-40e6-bb34-b700cdefb86a.png">

<img width="1625" alt="Screenshot 2023-01-24 at 1 28 22 AM" src="https://user-images.githubusercontent.com/43849911/214137418-99c7b9c5-5ca4-4343-9f06-b8f65a7a5907.png">

<img width="1003" alt="Screenshot 2023-01-24 at 1 28 47 AM" src="https://user-images.githubusercontent.com/43849911/214137508-9987c6bb-62f5-4697-9c30-e714cc4d8127.png">

<img width="1791" alt="Screenshot 2023-01-24 at 1 29 20 AM" src="https://user-images.githubusercontent.com/43849911/214137603-611fea55-33fe-4cdb-9a39-c6f1096b36fb.png">

<img width="562" alt="Screenshot 2023-01-24 at 1 32 15 AM" src="https://user-images.githubusercontent.com/43849911/214138247-e087760b-4116-4907-8557-5515dd223365.png">

```
./elasticsearch-reset-password -u elastic

This tool will reset the password of the [elastic] user to an autogenerated value.
The password will be printed in the console.
Please confirm that you would like to continue [y/N]y


Password for the [elastic] user successfully reset.
New value: tEkqcmVSrkgi*I8ciS6+
```

<img width="675" alt="Screenshot 2023-01-26 at 4 06 05 PM" src="https://user-images.githubusercontent.com/43849911/214815505-525b1149-3707-4f32-ac3b-1fad7d8c6005.png">


```
✅ Elasticsearch security features have been automatically configured!
✅ Authentication is enabled and cluster connections are encrypted.

ℹ️  Password for the elastic user (reset with `bin/elasticsearch-reset-password -u elastic`):
  ptCdqQ+I7OhIRvNe3t-_

ℹ️  HTTP CA certificate SHA-256 fingerprint:
  7c4b7a190c7e3ccaec121d44058b0b367a7aa99c4a1a6ccd5432436e8beba4e6

ℹ️  Configure Kibana to use this cluster:
• Run Kibana and click the configuration link in the terminal when Kibana starts.
• Copy the following enrollment token and paste it into Kibana in your browser (valid for the next 30 minutes):
  eyJ2ZXIiOiI4LjYuMCIsImFkciI6WyIxOTIuMTY4LjM0LjE5Mjo5MjAwIl0sImZnciI6IjdjNGI3YTE5MGM3ZTNjY2FlYzEyMWQ0NDA1OGIwYjM2N2E3YWE5OWM0YTFhNmNjZDU0MzI0MzZlOGJlYmE0ZTYiLCJrZXkiOiJNZHFsN1lVQllxRkprcDF3c0FZVDpJb2ExV0RKZFNiV0tzdkNLcHd0NGtRIn0=

ℹ️  Configure other nodes to join this cluster:
• On this node:
  ⁃ Create an enrollment token with `bin/elasticsearch-create-enrollment-token -s node`.
  ⁃ Uncomment the transport.host setting at the end of config/elasticsearch.yml.
  ⁃ Restart Elasticsearch.
• On other nodes:
  ⁃ Start Elasticsearch with `bin/elasticsearch --enrollment-token <token>`, using the enrollment token that you generated.
```

