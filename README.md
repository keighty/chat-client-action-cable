# README

Following this awesome tutorial on how to configure actionCable for websocket communication: https://dev.to/timnans/simple-rails-6-chat-application-with-action-cable-1b6m

Checkout these files for the changes necessary:
app/views/chats/create.js.erb
app/channels/room_channel.rb
app/javascript/channels/room_channel.js
app/views/chats/_form.html.erb
config/routes.rb
app/controllers/chats_controller.rb
app/views/chats/new.html.erb
