### Download your gmail inbox

    cd gmail
    ./gmail.py -m automatic -u me@gmail.com -p 'my_password_' -s ./email.avro.schema -f '[Gmail]/All Mail' -o /tmp/my_inbox_directory 2>&1 &
        
Run

    pig elasticsearch.pig
       