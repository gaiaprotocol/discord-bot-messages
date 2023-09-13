# Bot Messages

## Asset Verification Message (EN)
### URL
`https://discord.com/api/v10/channels/1136208335717281792/messages`

### Body
```
{
    "embeds": [
        {
            "title": "📢 Asset Verification",
            "description": "Dear members of the Gaia Protocol Discord Community, we are now assigning Discord Roles based on the asset holdings recorded on the blockchain. Through this, Gaia Protocol aims to provide a more transparent and fair community environment.\n\n**✅ Asset Verification Procedure**\n1. Please start the verification process by clicking the 'Start Connection and Verification' button below.\n2. Connect your crypto wallet on the popup site.\n3. Once the wallet connection and asset verification are complete, your Discord Role will be automatically assigned.\n\nIf you have any questions or encounter any problems, please feel free to ask in the community. Thank you!",
            "color" : 2829617
        }
    ],
    "components": [
        {
            "type": 1,
            "components": [
                {
                    "type": 2,
                    "label": "🔵 Start Connection and Verification",
                    "style": 5,
                    "url": "https://discord.com/api/oauth2/authorize?client_id=1135844231869644862&redirect_uri=https%3A%2F%2Fdiscord-asset-verification.gaia.cc%2F&response_type=code&scope=identify%20guilds.members.read"
                }
            ]
        }
    ]
}
```

## Asset Verification Message (KR)
### URL
`https://discord.com/api/v10/channels/1136208928120770632/messages`

### Body
```
{
    "embeds": [
        {
            "title": "📢 자산 보유 인증 안내",
            "description": "가이아 프로토콜 디스코드 커뮤니티 여러분, 우리 커뮤니티에서는 블록체인에 기록된 자산 보유량에 따라 디스코드 Role을 지정하고 있습니다. 이를 통해 가이아 프로토콜은 더욱 투명하고, 공정한 커뮤니티 환경을 제공하려 합니다.\n\n**✅ 자산 보유 인증 절차**\n1. 아래의 연결 및 인증 시작 버튼을 눌러 인증 절차를 시작하세요.\n2. 팝업되는 사이트에서 크립토 월렛을 연결해주세요.\n3. 월렛 연결 후 자산 보유 인증이 완료되면 디스코드 Role이 자동으로 지정됩니다.\n\n혹시 궁금하신 점이나 문제가 발생하신다면 언제든지 커뮤니티에 질문해 주세요.\n감사합니다!",
            "color" : 2829617
        }
    ],
    "components": [
        {
            "type": 1,
            "components": [
                {
                    "type": 2,
                    "label": "🔵 연결 및 인증 시작",
                    "style": 5,
                    "url": "https://discord.com/api/oauth2/authorize?client_id=1135844231869644862&redirect_uri=https%3A%2F%2Fdiscord-asset-verification.gaia.cc%2F&response_type=code&scope=identify%20guilds.members.read"
                },
                {
                    "type": 2,
                    "label": "⬢ D'CENT Wallet을 사용중이신가요?",
                    "style": 5,
                    "url": "[https://discord.com/api/oauth2/authorize?client_id=1135844231869644862&redirect_uri=https%3A%2F%2Fdiscord-asset-verification.gaia.cc%2F&response_type=code&scope=identify%20guilds.members.read](https://docs.gaiaprotocol.com/%ED%95%9C%EA%B5%AD%EC%96%B4%20%EB%AC%B8%EC%84%9C/%ED%99%80%EB%8D%94%20%EC%9D%B8%EC%A6%9D%20%EB%B0%A9%EB%B2%95/#dcent)https://docs.gaiaprotocol.com/%ED%95%9C%EA%B5%AD%EC%96%B4%20%EB%AC%B8%EC%84%9C/%ED%99%80%EB%8D%94%20%EC%9D%B8%EC%A6%9D%20%EB%B0%A9%EB%B2%95/#dcent"
                }
            ]
        }
    ]
}
```
