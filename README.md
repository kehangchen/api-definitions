## Commands

To combine multiple APIs into one:

``swagger-combine swagger-combine-conf.yaml -o swagger-combine-out.yaml``

To display the merged file from above action:

``redoc-cli serve swagger-combine-out.yaml``

To display the merged file from above action in github:

``redoc-cli serve https://raw.githubusercontent.com/kehangchen/api-definitions/master/swagger-combine-out.yaml``