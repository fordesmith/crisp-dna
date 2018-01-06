________________

TEST
----------
require 'slack_markdown'

processor = SlackMarkdown::Processor.new(
  on_slack_channel_id: -> (uid) {
    # TODO: use Slack API
    return { url: '/general', text: 'general' }
  },
  on_slack_user_id: -> (uid) {
    # TODO: use Slack API
    return { url: '/ru_shalm', text: 'ru_shalm' }
  },
  asset_root: '/',
  original_emoji_set: { ... },
)

processor.call("<@U12345> hello *world*")[:output].to_s
