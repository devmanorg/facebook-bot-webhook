# Facebook bot webhook

This is a simple Facebook Messenger Webhook, which allows you to receive and send messenges.

1. Use tutorials to get API key:
    - [�������]()
    - [english]()
2. Create [heroku](heroku.com) account and create app there.
3. Go to `Settings` section and add `Config Vars` pair: `PAGE_ACCESS_TOKEN` and token you got via first step.
4. Add another pair: `VERIFY_TOKEN` and any value you want.
5. Go to `Deploy` section and deploy that bot

Now click on `open app` button and you would get "Hello world" page.

If you not, use [heroku logs](https://devcenter.heroku.com/articles/logging#view-logs) to find bug.