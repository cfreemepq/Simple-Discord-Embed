const lib = require('lib')({token: process.env.STDLIB_SECRET_TOKEN});

await lib.discord.channels['@0.3.0'].messages.create({
  "channel_id": `${context.params.event.channel_id}`,
  "content": "",
  "tts": false,
  "embeds": [
    {
      "type": "rich",
      "title": `Discord simple embed code`,
      "description": `Simple Description`,
      "color": 0xdb1c1c,
      "fields": [
        {
          "name": `Simple field name`,
          "value": `Simple field value`
        }
      ],
      "image": {
        "url": `Simple image url`,
        "proxy_url": `Simple proxy url of the image`,
        "height": null,
        "width": null
      },
      "thumbnail": {
        "url": `Simple url of the image of your thumbnail`,
        "proxy_url": `Simple proxy url of ur thumbnail`,
        "height": null,
        "width": null
      },
      "author": {
        "name": `Simple name`,
        "url": `Simple url`,
        "icon_url": `Simple icon url`,
        "proxy_icon_url": `Simple proxy icon url`
      },
      "footer": {
        "text": `Simple name`,
        "icon_url": `Simple icon url`,
        "proxy_icon_url": `Simple proxy icon url`
      },
      "url": `Simple URL`
    }
  ]
});
