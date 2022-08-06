# Publisher-Subscriber-Pattern

There are 3 types of agents: publisher, broker and subscriber. Your solution will support
multiple publishers and subscribers and a single, centralized broker. Each entity will be a
process of its own.
Broker’s responsibility is to actively pull messages from publishers and push these over
to subscribers based on their preferences on topics. Every message is associated with
one and only one topic.
 Any publisher could post a message on any topic. Similarly, a subscriber may register for
one or more topics, which will occur upon connection to the broker. Besides this setup
task, topic management will be excluded entirely from this project.
 A subscriber should be online to get messages. A publisher should be online to post
messages. While subscribers and publishers enter and go as they like, broker will be
online all the time.
