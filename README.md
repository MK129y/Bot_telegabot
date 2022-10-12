# Bot_telegabot

# That command according to the following principle:
# 1. You have written `/find` command
# 2. If you are already in the search or have an active dialog, bot sends you 'Shut up!'
# 3. If not:
#   3.1. Bot sends you 'Finding...'
#   3.2. If there is no user in the search:
#       3.2.2. `freeid` updated with `your_chat_id`
#   3.3. If there is user in the search:
#       3.3.1. Both you and the user in the search recieve the message 'Founded!'
#       3.3.2. `users` updated with a {user_in_the_search_chat_id, your_chat_id}
#       3.3.3. `users` updated with a {your_chat_id, user_in_the_search_id}
#       3.3.4. `freeid` updated with `None`


команда по следующему принципу:
# 1. Вы написали команду `/find`
# 2. Если вы уже находитесь в поиске или у вас активный диалог, бот отправляет вам «Заткнись!»
# 3. Если нет:
№ 3.1. Бот отправляет вам сообщение "Найти..."
# 3.2. Если пользователя в поиске нет:
# 3.2.2. `freeid` обновлен с помощью `your_chat_id`
№ 3.3. Если в поиске есть пользователь:
# 3.3.1. И вы, и пользователь в поиске получаете сообщение «Основано!»
