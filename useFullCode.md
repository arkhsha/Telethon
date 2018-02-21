msgs = client.get_message_history('a_channel', limit=10000)

for msg in msgs:
    print(msg)
