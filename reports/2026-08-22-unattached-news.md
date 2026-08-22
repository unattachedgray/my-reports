# unattached.me 뉴스 — 2026-08-22

> 자동 발행: https://www.unattached.me/news/#2026-08-22

## AI

**오늘의 분석**

오늘 목록의 저류는 '소프트웨어는 느려도 된다'는 통념에 대한 반격이다. 버그를 얼마나 남길지 스스로 고른다는 Nolan Lawson의 도발, 100MB 미만을 노린 Rust Glancer, 50ms 이하로 응답하는 TTS, 그리고 TUI 대신 네이티브 UI를 만들라는 주장이 같은 방향을 가리킨다. 다만 결은 갈린다. LLM이 만든 코드도 충분히 빠르다는 낙관과, 4개월을 들여 메모리를 100배 줄인 장인적 작업은 같은 '빠름'을 말하지 않는다. 전자는 도구가 비용을 없앴다고 보고, 후자는 여전히 사람의 설계가 그 차이를 만든다고 본다.

규제 쪽에서는 방향이 더 또렷하다. OpenAI가 한때 반대하던 캘리포니아 SB 53을 이제는 강화하라 요구하고, 동시에 주요 연구소들은 악성 모델 억제 계획을 공개하길 거부한다는 연구가 나왔다. 자율에 맡긴 안전이 실제로는 공개조차 되지 않는다는 정황은, 강제력 있는 기준이 왜 필요한지를 역설적으로 스스로 입증한다. 기업의 입장 전환 역시 순수한 선의보다는 규칙이 어차피 오리라는 판단이 읽히는 대목이다.

반대로 에이전트 서사에서는 과열의 징후가 두드러진다. Faraday가 논문 재현에서 Anthropic·OpenAI를 눌렀다는 벤더 발표, 사무실을 통째로 복제한다는 하니스, 하버드의 699달러짜리 AI 아바타 강사, 그리고 ElevenLabs를 비꼰 'TwelveLabs·ThirteenLabs' 풍자가 한 흐름에 놓인다. 자화자찬 벤치마크와 이름 붙이기 경쟁은 실제 채택과는 다른 층위의 이야기다. 결국 앞으로 주시할 하나는 SB 53의 처리 결과다. 자율 규제의 공백을 법이 메울지, 아니면 다시 업계의 홍보 문구로 남을지가 여기서 갈린다.

### 🆕 Claudette: Claude가 BuzzFeed 기사처럼 말하지 않게 만들기

Claudette는 GitHub에 공개된 프로젝트로, Claude의 출력 스타일을 BuzzFeed 기사와 같은 어조에서 벗어나게 하는 프롬프트를 제공한다.

**시사점** — Claude 사용자와 프롬프트 엔지니어가 스타일 제어에 활용 가능

[Claudette: Make Claude stop talking like a BuzzFee](https://github.com/adnanakil/nobuzz/blob/main/README.md)

### There's no reason for software to be slow anymore

Article URL:  https://danluu.com/perf-opt/  
 Comments URL:  https://news.ycombinator.com/item?id=49395628  
 Points: 227 
 # Comments: 168

[There's no reason for software to be slow anymore](https://danluu.com/perf-opt/)

### New Worlds: We are living in the future of J.G. Ballard or William Gibson

Article URL:  https://precastreinforced.co.uk/2026/08/16/new-worlds/  
 Comments URL:  https://news.ycombinator.com/item?id=49387525  
 Points: 232 
 # Comments: 164

[New Worlds: We are living in the future of J.G. Ba](https://precastreinforced.co.uk/2026/08/16/new-worlds/)

### Rust Glancer: Rust LSP using 100x less RAM

https://matklad.github.io/2026/08/21/rust-glancer.html  
 
 Comments URL:  https://news.ycombinator.com/item?id=49393052  
 Points: 223 
 # Comments: 49

[Rust Glancer: Rust LSP using 100x less RAM](https://rust-glancer.github.io/blog/hello-world/)

### Canada suspends trade negotiations with USA and match tariffs dollar for dollar

Article URL:  https://www.pm.gc.ca/en/news/statements/2026/08/21/statement-prime-minister-carney-canada-us-trade-negotiations  
 Comments URL:  https://news.ycombinator.com/item?id=49398304  
 Points: 216 
 # Comments: 114

[Canada suspends trade negotiations with USA and ma](https://www.pm.gc.ca/en/news/statements/2026/08/21/statement-prime-minister-carney-canada-us-trade-negotiations)

### Scientists release biggest 2D map of the universe

Direct link to Legacy Survey Sky Viewer:  https://viewer.legacysurvey.org  
 
 Comments URL:  https://news.ycombinator.com/item?id=49392200  
 Points: 221 
 # Comments: 60

[Scientists release biggest 2D map of the universe](https://newscenter.lbl.gov/2026/08/10/scientists-release-biggest-2d-map-of-the-universe/)

### Stop Making TUIs

Article URL:  https://sockpuppet.org/blog/2026/08/20/stop-making-tuis/  
 Comments URL:  https://news.ycombinator.com/item?id=49384210  
 Points: 252 
 # Comments: 331

[Stop Making TUIs](https://sockpuppet.org/blog/2026/08/20/stop-making-tuis/)

### ⚠ 프런티어 AI 연구소, 악성 모델 억제 방안 공개 거부

새로운 연구에 따르면 주요 AI 연구소들은 악성 모델을 억제하기 위한 공개된 계획이 거의 없다고 밝혀졌다. 이는 AI 시스템이 예기치 않은 위험을 초래할 경우 대비가 부족함을 시사한다.

**시사점** — 대형 AI 기업과 투자자는 2026년 4분기까지 모델 안전성 검증 프로세스를 도입할지 여부를 주시해야 한다.

[Frontier AI labs still won’t say how they’d contai](https://techcrunch.com/2026/08/22/frontier-ai-labs-still-wont-say-how-theyd-contain-a-rogue-model/)

### 🆕 OpenAI, 캘리포니아 AI 안전법 강화 촉구

OpenAI는 캘리포니아 주가 현재 논의 중인 AI 안전법 SB 53을 강화할 것을 요구했다. 이 회사는 과거 해당 법안을 반대했지만, 최근 입장을 바꾸었다.

**시사점** — 캘리포니아 내 AI 기업과 스타트업은 강화된 규제 적용 전까지 컴플라이언스 비용 증가를 주시해야 한다.

[OpenAI says California should strengthen its AI sa](https://techcrunch.com/2026/08/22/openai-says-california-should-strengthen-its-ai-safety-bill/)

### ⚠ OTel이 기대에 미치지 못함

OpenTelemetry(OTel) 도입 현황이 부진하고, 저자는 이를 정리한 스프레드시트를 공개했다. 해당 자료는 주요 클라우드 서비스와 기업들의 OTel 채택 현황을 비교한다.

**시사점** — 관측 솔루션을 도입하려는 기업들은 2026년 4분기까지 OTel 대안을 검토해야 함

[OTel isn’t going well](https://matduggan.com/otel-isnt-going-well-and-i-made-a-spreadsheet-about-it/)

### 🆕 Inherent, DeepMind 출신이 설립한 AI ‘팀메이트’ Faraday, Anthropic·OpenAI를 능가

Inherent가 발표한 AI 에이전트 Faraday가 연구 논문 재현 작업에서 Anthropic과 OpenAI 모델을 능가했다. DeepMind 출신이 설립한 영국 AI 랩이 개발했으며, 논문 복제 능력이 향상된 것으로 평가받았다.

**시사점** — 연구기관은 Faraday를 활용해 논문 재현 효율을 높일 수 있다.

[Inherent, founded by DeepMind alumni, says its AI ](https://techcrunch.com/2026/08/22/inherent-founded-by-deepmind-alumni-says-its-ai-teammate-just-outperformed-anthropic-and-openai-at-replicating-research/)

### 🆕 Munder Difflin, 사무실 복제용 에이전트 하니스 출시

Munder Difflin은 사무실 업무를 복제된 클론으로 운영할 수 있는 에이전트 하니스를 제공한다. 해당 서비스는 웹사이트와 커뮤니티에서 199점의 관심을 받았다.

**시사점** — 기업은 Munder Difflin을 도입해 사무 자동화를 시도할 수 있다.

[Munder Difflin – Agent harness to run an office of](https://munderdiffl.in/)

### ElevenLabs, TwelveLabs, ThirteenLabs

Article URL:  https://quantumi.sh/public/labs.html  
 Comments URL:  https://news.ycombinator.com/item?id=49400408  
 Points: 224 
 # Comments: 74

[ElevenLabs, TwelveLabs, ThirteenLabs](https://quantumi.sh/public/labs.html)

### Hook, hold, harvest and hide: Meta's alleged strategy laid out in first week

Article URL:  https://www.theguardian.com/technology/2026/aug/22/meta-trial-children-privacy  
 Comments URL:  https://news.ycombinator.com/item?id=49398904  
 Points: 192 
 # Comments: 153

[Hook, hold, harvest and hide: Meta's alleged strat](https://www.theguardian.com/technology/2026/aug/22/meta-trial-children-privacy)

### Canada will match US tariffs 'dollar for dollar' as trade talks break down

https://www.pm.gc.ca/en/news/statements/2026/08/21/statement...  
 
 Comments URL:  https://news.ycombinator.com/item?id=49397074  
 Points: 241 
 # Comments: 886

[Canada will match US tariffs 'dollar for dollar' a](https://www.bbc.com/news/articles/cvgvyy4x2mvo)

### 🆕 텍스트‑투‑스피치 모델을 50 ms 이하로 응답하도록 만든 방법

Nari Labs는 텍스트‑투‑스피치(TTS) 모델의 응답 시간을 50 ms 미만으로 단축한 기술을 공개했다. 해당 최적화는 지연 시간을 크게 낮추어 실시간 음성 서비스에 적합하도록 설계되었다.

**시사점** — 실시간 음성 인터랙션을 제공하는 스타트업과 대형 플랫폼이 지연 50 ms 이하 모델 도입을 검토할 필요가 있다.

[How we made a text-to-speech model respond in sub-](https://nari-labs.com/blog/qwen3-tts-speed-cost-frontier/)

### Harvard’s $699 startup bootcamp offers AI avatars of its instructors

In the HBS Foundry program, AI avatars provide feedback during practice pitches and board meetings.

[Harvard’s $699 startup bootcamp offers AI avatars ](https://techcrunch.com/2026/08/22/harvards-699-startup-bootcamp-offers-ai-avatars-of-its-instructors/)

### Scrap

Article URL:  https://twitter.com/moxie/status/2091218652133732491  
 Comments URL:  https://news.ycombinator.com/item?id=49402189  
 Points: 298 
 # Comments: 152

[Scrap](https://twitter.com/moxie/status/2091218652133732491)

### A Friendly Introduction to Racket

Article URL:  https://geometridae.bearblog.dev/a-friendly-introduction-to-racket/  
 Comments URL:  https://news.ycombinator.com/item?id=49399898  
 Points: 185 
 # Comments: 92

[A Friendly Introduction to Racket](https://geometridae.bearblog.dev/a-friendly-introduction-to-racket/)

### 새 MCP 로드맵 공개

모델 컨텍스트 프로토콜(MCP) 프로젝트가 공식 블로그에 새 로드맵을 공개했다. 해당 게시물은 해커뉴스에서 173점을 받았다.

[New MCP Roadmap](https://blog.modelcontextprotocol.io/posts/mcp-roadmap/)

## 한국

**오늘의 분석**

오늘 뉴스의 축은 공적 시스템이 스스로의 실패를 걸러내지 못하는 장면들이다. 제주 30대 여성 실종사건은 담당 경찰관의 허위 종결로 실종자가 숨진 채 뒤늦게 발견됐고, 긴급체포된 경찰관에게서 또 다른 실종·가정폭력 신고의 셀프 종결과 자료 삭제 정황까지 드러났다. 국가수사본부장이 제주경찰청을 찾아 사과했지만, 이는 개인의 일탈이라기보다 초동 대응과 기록 관리의 구조적 공백에 가깝다. 제주항공 참사 600일에도 유해 1740점만 수습된 채 책임자 기소조차 이뤄지지 않았다는 소식, 소아외과 전임의가 수년째 0명이라는 의료 공급 절벽과 나란히 놓으면, 안전과 책임을 담보해야 할 제도가 곳곳에서 헐거워진 흐름이 보인다.

반면 재난 현장의 대응은 상대적으로 기민하다. 거제·통영 수해복구에 이틀간 4800여 명이 투입되고 특별재난지역 추가 선포가 추진되며, 현대차그룹의 성금과 전세사기·고용위기 지역 지원책도 이어졌다. 자원 동원은 빠른데 책임 규명은 더딘 이 비대칭이 오늘의 인상이다. 경제 쪽에서도 환율 하락과 증시 변동성 속 안전자산 쏠림, 고가 법인주택 42%가 사주일가 '황제사택'이라는 국세청 첫 전수점검 결과, 3년째 낮아지는 '갑질 감수성'이 겹친다. 형평의 규칙이 느슨해질수록 시장과 공공 모두에서 신뢰가 어디로 빠져나가는지를 보여주는 대목이다.

주시할 하나는 국가수사본부의 이번 점검이 담당자 문책에 그칠지, 초동 대응 부실을 걸러내는 제도 개선으로 이어질지다.

### 🆕 부산발 북극항로 시범운항선 출항…35% 단축 효과 두고 과제 7가지

부산에서 북극항로 시범운항선이 출항했다. 부산시와 팬스타가 협력하며 약 45일간 운항한다. 항로는 기존 대비 35% 단축 효과가 있으나 7개의 과제가 지적됐다.

**시사점** — 45일 시범운항 결과가 팬스타와 국내 해운사의 북극항로 상업화 판단을 가른다

[오늘 닻 올리는 북극항로…‘35% 단축’ 뒤에 가려진 7개의 벽 - 해사신문](https://news.google.com/rss/articles/CBMia0FVX3lxTE96eGp6TVFBa1dyM0puUXN0U3pJQmN3T3NaYTZyY1FoSFdUSzIxSlBqLXoyT18zcUF3U2dDNVc1cVVzWWcwdHNMN19fbXJqQ2w3dHI5RlE1TXFJdkQtUjdGYWl4dFhFN1dIcXJV?oc=5)

### 🆕 경국대, 의대 정원 50명만 신청…전남·광주 신설 여지 남겨

경국대가 의대 정원으로 50명만 신청했다. 전남·광주 의대 신설 여지를 남겼다. 지역에서는 전남의대가 무산 위기라는 지적이 나온다.

**시사점** — 경국대의 50명 신청으로 전남·광주 주민이 요구한 서부권 의대·병원 신설 여부가 향후 정원 배정에 달렸다

[경국대, 의대 정원 50명만 신청…전남광주 신설 여지 남겨 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE5Yd3VTN1B6VHJELUNlaHBNZVV0NVZmbWpZVUNDZXZXWWduRWF3QmFXNl9mOTdwOUJGcTd2SU1YWTAyc0c1dVFyMEhLT2t1WkNkd0RFamZISHVHV1XSAWBBVV95cUxQd2pFTXIySlYxSi1NRlE0TTZ4R1dQS3REdEpFcEp0RURVRkowNDQyeTJsY3hFeUtkTjJOUy1LdWtUZDc4TlBNRFdCekE4U2E4MFN4V0NSUXY4VnhxMmtvSkU?oc=5)

### 🆕 전투기 조종사 구한 스리랑카 근로자, 韓 장기 체류 자격 받아

비상탈출한 전투기 조종사를 구조한 스리랑카 근로자들이 한국 장기 체류 자격을 받았다. 추락한 전투기 조종사를 구한 공로다. 정성호는 생명을 구한 헌신에 보답한다고 밝혔다.

**시사점** — 정성호 명의로 외국인 근로자에 장기체류 비자 특전을 준 사례로 외국인력 체류 정책의 재량 판단 기준이 된다

[‘조종사 구한 영웅’ 스리랑카 근로자, 韓 장기 체류 자격 받아 - 조선일보](https://news.google.com/rss/articles/CBMihwFBVV95cUxQWjVyLVgwNlJLOWdIY2RsUlUzRkliY2dQdFN4Mm5QOHBTVENsT2hVWllXZzdudjBTXzFmakRId1FlR3cyYlNseGJlRmM4TmxfbGY3bEFmMGpoejBYN1hwdnhRcFE0ZmtCazJMY0RieGx6dEtUX3hNeXRIY1RlaUVKWlNJSXZiaHM?oc=5)

### 🆕 광교 나일왕도마뱀 11일 만에 포획…30대 주인 위법 여부 검토

광교신도시에 출몰한 외래종 나일왕도마뱀이 포획됐다. 11일간 수색 끝에 홍재도서관 인근 하천변에서 70㎝ 길이 개체가 붙잡혔다. 수원시와 소방 당국이 30대 주인의 위법 여부를 검토한다.

**시사점** — 수원시가 30대 주인의 위법 여부를 검토하는 결과가 외래종 사육·관리 책임 기준을 가른다

[‘광교 나일왕도마뱀’ 11일만에 붙잡혀…30대 주인 위법여부 검토](https://www.donga.com/news/Society/article/all/20260822/134523508/1)

### 🔴 미국·캐나다 막판 무역협상 실패···캐나다산 50% 관세 현실화

미국과 캐나다의 무역협상이 결렬돼 캐나다산 제품에 50% 관세가 부과될 전망이다. 이로써 양국 간 교역 규모가 급감할 가능성이 있다.

**시사점** — 한국 수입업체는 캐나다산 원자재 대체 공급처를 급히 찾을 필요가 있다.

[미국·캐나다 막판 무역협상 실패···캐나다산 50% 관세 현실화](https://www.khan.co.kr/article/202608221354001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 인천 서해5도 호우주의보 7시간 만에 해제

인천 서해5도에 발효됐던 호우주의보가 7시간 만에 해제되었다. 기상청은 오후 1시 20분을 기해 해제했으며, 오전 6시 15분에 발효했다.

**시사점** — 인천 서해5도 주민은 22일 해제된 호우주의보에 따라 농업 방수 대비를 재조정해야 한다.

[인천 서해5도 호우주의보 7시간 만에 해제](https://www.donga.com/news/Society/article/all/20260822/134523528/1)

### 🆕 운전하다 빵 터지는 이색표지판…‘인제 신남’?

전국 고속도로와 국도에 설치된 이색 지명 표지판이 SNS와 온라인 커뮤니티에서 화제를 모으고 있다. ‘인제 신남’ 등 낯선 표지판이 운전자의 눈길을 끈다.

**시사점** — 운전자는 ‘인제 신남’ 등 이색 표지판을 보고 혼동할 가능성이 있어 교통안전 캠페인에 활용될 수 있다.

[운전하다 빵 터지는 이색표지판…‘인제 신남’?](https://www.donga.com/news/Society/article/all/20260822/134523547/1)

### 🆕 ‘에어컨을 얼마나 세게 틀길래?’…공항이 유독 춥게 느껴지는 진짜 이유

여름철 인천공항에서 에어컨이 과다 가동돼 승객들이 추위를 느끼는 현상이 발생했다. 이는 에어컨 설정 온도가 비정상적으로 낮게 유지된 것이 원인이다.

**시사점** — 인천공항은 여름철 에어컨 과다 가동으로 승객 불편이 커져 승객 만족도 조사에 영향을 줄 수 있다.

[“에어컨을 얼마나 세게 틀길래?”…공항이 유독 춥게 느껴지는 진짜 이유](https://www.khan.co.kr/article/202608221400001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 폭우 닷새 지난 거제, 침수 복구 계속…주민 “냄새 언제 빠질지”

지난 17일 기록적 폭우로 침수된 경남 거제시 둔덕면 하둔리에서 닷새째 복구 작업이 진행됐다. 곽쌍수 씨(76) 등 주민들은 집 안에 남은 악취와 2차 피해를 우려했다.

**시사점** — 거제 둔덕면 침수 주민이 닷새째 복구 중으로, 악취 제거와 추가 강우가 남은 변수다.

[찜통더위 뚫고 복구 구슬땀…거제 주민들 “냄새는 언제 빠질지”](https://www.donga.com/news/Society/article/all/20260822/134523647/1)

### 🆕 국제유가 오르는데 기름값 상한은 동결…손실보전 규모 주목

정부가 국제유가 상승에도 9차 석유제품 최고가격을 동결했다. 중동 정세 불확실성으로 원유 도입 비용이 오르지만 물가와 민생 부담을 고려해 두 차례 연속 최고가격을 묶었다.

**시사점** — 유가가 오르는데 최고가격을 2회 연속 동결해 정유사 손실보전 규모가 다음 변수다.

[국제유가 오르는데 기름값 상한은 그대로…손실보전 규모는?](https://www.donga.com/news/Economy/article/all/20260822/134523584/1)

### 🆕 ‘회장님차’ 경쟁…제네시스 GV90에 벤츠 S클래스·BMW 7시리즈

제네시스 GV90과 메르세데스-벤츠 S-클래스, BMW 7시리즈가 올 하반기 쇼퍼드리븐 시장에서 정면승부를 펼친다. 주요 완성차 브랜드가 플래그십 모델을 잇달아 선보인다.

**시사점** — 제네시스 GV90·벤츠 S클래스·BMW 7시리즈가 올 하반기 쇼퍼드리븐 시장에서 맞붙어 판매 성적이 관전 포인트다.

[역대급 ‘회장님車’ 전쟁…제네시스 GV90에 벤츠 신형 S클래스·BMW 7시리즈 까지](https://www.donga.com/news/Economy/article/all/20260822/134523591/1)

### 🆕 소아외과 전임의 수년째 0명…소아 의료 '공급 절벽' 우려

여러 매체가 소아 의료 붕괴 실태를 보도했다. 소아외과는 수년째 전임의가 0명이고, 소아 수술용 의료기기 공급도 끊기고 있다. 소아과 의사들은 정부의 현장 인식을 비판했다.

**시사점** — 소아외과 전임의 0명과 소아 의료기기 공급 절벽이 지방 소아 수술 병원의 존폐 분기점이다

[현장 반대 정책 내고 '박수치라'?…정부 인식에 "비참한" 소아과 의사들 - 청년의사](https://news.google.com/rss/articles/CBMib0FVX3lxTE9mNjlOU0hJLXdvNmo0VFVRSGN1Z3NOeGlaZmd2N24wdTRJT2xrbFUwNF9OLUJnc3RhWV9QUEp4cWQ2WEY2Rjc2Q09iVmdaRlN3QVFKRkpDdDA4b2pyMGJlV3B5R1ZuUzBNZDFhR2hnWdIBc0FVX3lxTE80emtGMmxMek5GUGhGYjVQTU9VTlU4dmQ4SGVNU3VPVlZOX2d3TzdEaTMxN2Rhb2RqSFZKZ0xxcFE3T0ttZDhaX3NsemxPQnlHMkZTNl93SGh3WHZOXzJ2dFVURmhTN0dqSWU1V1ppUGZxdGM?oc=5)

### 🆕 봉은사 주지 지낸 명진스님 입적…제주서 프리다이빙 사고

봉은사 주지를 지낸 명진스님이 22일 입적했다. 세수 76세, 법랍 52년이다. 스님은 이날 오전 제주도 바다에서 프리다이빙을 하다 사고를 당했다.

[봉은사 주지 지낸 명진스님 입적···제주서 프리다이빙 사고](https://www.khan.co.kr/article/202608221604011/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news) | [봉은사 주지 지낸 명진스님 입적…제주서 프리다이빙 사고](https://www.donga.com/news/Society/article/all/20260822/134523662/2)

### 박완수 경남지사, 거제 등 특별재난지역 추가 선포 추진

박완수 경남지사가 특별재난지역 추가 선포를 위해 최선을 다하겠다고 밝혔다. 거제 포도 농가는 침수 피해로 어려움을 겪고 있다.

**시사점** — 특별재난지역 추가 선포 여부가 거제 침수 포도 농가의 복구 지원 규모를 가른다

[박완수 경남지사 "특별재난지역 추가 선포되도록 최선" - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTFBNSHI0UlRiT0gzUlRLSzdjYzVJZVRmaFV1Wk5YN3BNck9oSHpyUGZPQWNTNE51bW5ReFNLcU5iLWNIX0pvR1ZqM29EZ3pzVzdxTk8zTXNFTlZQeUnSAWBBVV95cUxNeDEtVXRtTklIQlYyaXBkSm5LY3o0UFp2ZUgxdmNJV2sxSkt2aWU1SHg5NUtRN29QM201bDBRY3FYTTh5a3VTei1DZG9BT2QzMWpFTlY1cmxkUHpObHNnTnM?oc=5)

### 🆕 경기도교육청 교권보호전담관 공식 출범

교육활동 침해를 당한 교원을 사안 발생부터 종결까지 1대1로 전담 지원하는 경기도교육청 교권보호전담관이 공식 출범했다.

**시사점** — 교권 침해를 당한 경기도 교원이 사안 종결까지 1대1 지원을 받는 제도다

[‘참교육’ 현실판 된다···경기도교육청, 교권보호전담관 공식 출범](https://www.khan.co.kr/article/202608221524001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 제주 실종 장미란씨 가족에 “신음소리 들려주겠다” 협박한 10대 검거

제주에서 석 달 넘게 실종 상태인 장미란씨(37)의 가족에게 ‘신음 소리를 들려주면 실종자를 찾게 해주겠다’고 연락한 10대 남성이 경찰에 붙잡혔다. 이 사건은 실종신고 허위 종결 등 부실 초동 대응 논란 속에 3개월째 행방이 묘연한 상태다.

**시사점** — 부실 초동 대응 논란이 이어진 사건으로, 검거된 10대 남성의 범행 동기와 한림항 집중 수색의 진척이 관건이다.

[제주 실종여성 가족에 “신음소리 들려달라” 연락한 10대 남성 검거](https://www.khan.co.kr/article/202608221658001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### ⚠ 수도권·강원 곳곳 강한 비…세종 남부 등 호우주의보

22일 수도권과 강원 곳곳에 강한 비가 내려 세종 남부, 경기 가평, 경북 울진 등에 호우주의보가 내려졌다. 백령도 86㎜, 화성 66.5㎜ 등 많은 비가 기록됐고 하천 범람과 침수 주의가 당부됐다.

**시사점** — 수도권 출근·등교 시간대 침수와 하천 범람 위험이 커, 백령도 86㎜ 등 누적 강수량 추이를 주시해야 한다.

[세종 남부에 호우주의보 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE9OSTEtS2hiV2JIeTJQMldUNGlfbVl2d3ZPU2RXT2FhbFNhazhKQXlsajVYVmtjZDRjTUp6OTRXYThabGdSVEpYS3VHSWpXMkthQlFPZk14ck94SnPSAWBBVV95cUxNa1VVakQ1QWZiRTNrRzhEV1llX0hPUE9GY0pBb1JZWko5WUZwZmhSUG1rX1F6b0FUVzlybW9HY1RGUU9sN3BPRmJIR0pBVThPRDQwd092Q3ZKTS1BaVhjMGU?oc=5)

### 🆕 Z세대 구직자 70% “AI에 고민·속마음 털어놨다”

채용 플랫폼 진학사 캐치가 Z세대 구직자 1110명을 조사한 결과, 상당수가 생성형 AI에 고민을 털어놓은 경험이 있고 AI의 조언을 행동으로 옮긴 사례도 많았다. 하루에도 여러 번 AI를 이용한다는 응답도 나왔다.

**시사점** — Z세대 구직자 1110명 중 70%가 AI에 속내를 털어놨다는 조사로, 청년 상담·정신건강 서비스 수요 변화의 지표가 된다.

[AI 의존 괜찮나…“Z세대 이용자 70%, 고민·속마음 털어놔”](https://www.donga.com/news/Society/article/all/20260822/134523690/1)

### 🆕 김지수, 브렌트포드 1군 포함…EPL 코리안리거 계보 잇는다

한국 대표팀의 미래로 평가받는 김지수(22)가 잉글랜드 프리미어리그(EPL) 브렌트포드 1군 명단에 포함됐다. 브렌트포드는 21일 공식 채널로 2026~2027시즌 1군 멤버와 등번호를 공개했다.

**시사점** — 브렌트포드가 김지수를 1군 명단에 올려, 2026~2027시즌 그의 EPL 데뷔 여부와 출전 시간이 관전 포인트다.

[김지수, 브렌트포드 1군 포함…韓 EPL 계보 이어간다](https://www.donga.com/news/Sports/article/all/20260822/134523687/1)

### 김영배, 오세훈 만난 뒤 “용산공원 1㎝도 양보 안 된다며 자기 정치”

더불어민주당 서울시당위원장인 김영배 의원이 22일 주택 공급 등 서울시 현안을 논의하기 위해 오세훈 시장과 회동했으나 이견을 좁히지 못했다. 김 의원은 22일 국회에서 기자들과 만나 “오 시장과 오찬을 하며 격의 없이 주택 공급 정책과 청년 주택 주거의 문제를 포함해 시민을 위해 함께할 수 있는 일에 대해 의견을 교환했다”고 말했다. 그는 “주택 공급과 관련해 함께 검토해야 할 여러 논쟁에 관해 논의가 있었다”며 “결론적으로 큰 합의에 이르는 것은 조금 어려웠다”고 했다. 특히 “용산과 용산 정비

[김영배, 오세훈 만난 뒤 “용산공원 1㎝도 양보 안 된다며 자기 정치”](https://www.donga.com/news/Politics/article/all/20260822/134523712/2) | [김영배 "吳, 1cm도 양보 못한다며 자기 정치"‥오세훈 "재개발·재건축 협력 공감대" -](https://news.google.com/rss/articles/CBMieEFVX3lxTFBucklPeklqWHpKTFdncWVtVHcyUUk5MHIzeHhNTXNTdkYtN0hpRXdJemlNVzV1VEZ0VnEzZWpyNXl6MGg0MHpFVXFaRUlCRG9KRlFObGpfRFp5Tk5ndDlSWGRCVnVrR1BzVWZvQldoT0VvaTN5aVRsN9IBeEFVX3lxTE5yQmRvSXZfUkZVSERpUV9zS2Y0MC1Ic3hCQ2FxZTV0MUFRcHpyOWlSQUNNM1ZVSXM0alp0UGthUjRZUEFZRDlZVFlaNTI0bXhvbmRTb1IwWFhJNTJjMHptQlpMNFplMDF4d3NqaXg3RXhWcDY5d0JRSQ?oc=5)

### ‘A Little Priest’를 열창하는 대학·일반부 단체 김예진 외 1명

경향신문 주최, 스포츠경향 주관으로 22일 서울 강동구 호원아트홀에서 열린 제9회 경향뮤지컬콩쿠르 본선에서 대학·일반부 단체 김예진 외 1명이 뮤지컬 <스위니 토드>의 ‘A Little Priest’를 부르고 있다. 한수빈 기자

[‘A Little Priest’를 열창하는 대학·일반부 단체 김예진 외 1명](https://www.khan.co.kr/article/202608221818001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 데오드란트는 땀 줄여준다?…“잘못 아신 겁니다”

덥고 습한 여름에 땀 관리를 위해 데오드란트를 사용하는 경우가 많다. 데오드란트와 땀 분비 억제제는 성분과 목적이 아예 다르기 때문에 목적에 따라 올바르게 선택하는 것이 중요하다. 22일 식품의약품안전처 유튜브에 따르면 데오드란트는 땀 자체를 나지 않게 하는 것이 아니라 땀으로 인한 냄새를 가려주는 화장품으로 이해하는 것이 옳다.땀 분비 억제제 같은 경우에는 화학적으로 땀샘을 일시적으로 막아 물리적인 땀 배출을 줄여주는 의약외품 또는 일반의약품이다. 따라서 목적을 혼동해서 쓰면 효과를 보지 못하거

[데오드란트는 땀 줄여준다?…“잘못 아신 겁니다”](https://www.donga.com/news/It/article/all/20260822/134523740/1)

### 美연방법원, 75개국 이민 비자 발급 중단 제동…백악관 침묵

미국 연방법원이 21일(현지 시간) 도널드 트럼프 행정부가 75개국 출신 이민자에 부과한 비자 발급 금지 조치를 무효화했다. 해당 정책에 따라 이미 비자 발급을 거부당한 사례도 효력이 없다고 판단했다.뉴욕타임스(NYT) 등 현지 언론에 따르면 이날 뉴욕 맨해튼 연방지방법원 제네트 바르가스 판사는 국무부의 비자 발급 제한 조처는 법률에 어긋난다고 판단했다. 바르가스 판사는 61페이지 분량의 판결문에서 국무부가 비자 발급을 중단하며 제시한 근거, 즉 대상 국가 출신 이민자들이 공공 혜택을 받을 가능성

[美연방법원, 75개국 이민 비자 발급 중단 제동…백악관 침묵](https://www.donga.com/news/Inter/article/all/20260822/134523737/1)

### “신음소리 들려주면 찾아주겠다”…제주 실종자 가족에 17차례 장난전화 건 10대 검거

제주에서 실종된 30대 여성의 가족에게 “신음소리를 들려주면 실종자를 찾게 해주겠다”는 내용의 문자 메시지와 전화를 반복한 피의자가 경찰에 붙잡혔다.22일 경찰청 국가수사본부는 제주 30대 여성 실종사건과 관련해 실종자 가족에게 허위 제보성 문자메시지와 전화를 반복한 피의자(10대 남성)를 특정해 검거했다고 밝혔다.피의자는 전날 실종자 가족이 공개한 연락처로 ‘신음소리를 들려주면 실종자를 찾게 해주겠다’는 내용의 문자메시지와 전화를 총 17차례 반복적으로 보내 불안감을 유발했다. 경찰은 피의자인 

[“신음소리 들려주면 찾아주겠다”…제주 실종자 가족에 17차례 장난전화 건 10대 검거](https://www.donga.com/news/Society/article/all/20260822/134523734/2)

### 스페인 지로나 김민수, 이적설에도 코르도바전 맹활약

한국 남자 축구의 미래로 평가받는 김민수(20)가 스페인 프로축구 라리가 2(2부 리그) 지로나FC와 코르도바전에서 짙은 존재감을 과시했다.지로나는 22일(한국 시간) 스페인 코르도바의 에스타디오 누에보 아르칸헬에서 열린 코르도바와의 2026~2027시즌 라리가 2 2라운드 원정 경기에서 1-2로 패배했다.지로나는 1무1패(승점 1)를 기록하면서 리그 16위에 그쳤다.전반 12분 빅터 산체스, 전반 37분 디에고 브리에게 연속골을 내주며 끌려간 지로나는 후반 40분 야세르 아스프리야의 만회골이 나

[스페인 지로나 김민수, 이적설에도 코르도바전 맹활약](https://www.donga.com/news/Sports/article/all/20260822/134523730/1)

### 국힘 “李, ‘노웅래 무죄’에 숟가락 얹어 검찰 무력화…사법 방탄 멈추라”

국민의힘은 22일 이재명 대통령이 불법 정치자금 수수 혐의로 기소된 뒤 항소심에서 무죄를 선고받은 노웅래 전 더불어민주당 의원에게 공천 배제에 대해 사과한 것과 관련해 “노웅래 무죄에 숟가락 얹어 검찰 무력화 나선 이 대통령은 사법 방탄을 멈추라”라고 했다.박성훈 수석대변인은 이날 논평을 내고 “대통령이 판결의 본질은 외면한 채 기다렸다는 듯 검찰을 악마화하고 특정 정치인의 재판 결과를 검찰 무력화와 사법 방탄의 재료로 삼는 것이 과연 정상적인 국정인가”라며 이같이 말했다.박 수석대변인은 “이번 

[국힘 “李, ‘노웅래 무죄’에 숟가락 얹어 검찰 무력화…사법 방탄 멈추라”](https://www.donga.com/news/Politics/article/all/20260822/134523727/1)

### 제주 실종사건 허위종결 경찰관 긴급체포…'셀프종결' 다른 사건도 드러나

제주에서 3개월째 행방이 묘연한 장미란씨 실종사건을 허위로 종결한 의혹을 받는 담당 경찰관이 긴급체포됐다. 이 경찰관은 또 다른 실종사건도 허위로 종결한 정황과 관련 자료를 삭제한 정황이 확인됐다. 앞서 실종여성 가족에게 17회 장난전화·문자를 보낸 10대도 체포됐다.

**시사점** — 실종 3개월째 미제인 사건에서 담당 경찰관의 '셀프종결'과 자료 삭제 정황이 드러나, 제주경찰의 감찰·수사 결과가 다음 분수령이다.

[제주 여성 실종사건 허위종결한 경찰관 긴급체포](https://www.khan.co.kr/article/202608221909001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 여수국가산단 화력발전소 화재…석탄 분진 발화 추정

22일 오후 4시8분께 전남 여수시 중흥동 여수국가산업단지 내 발전소에서 불이 났다. 소방당국은 인력 70여 명과 화학소방차 등 장비 27대를 동원해 오후 6시11분께 초기 진화했다. 소방 당국은 석탄 분진 발화를 화재 원인으로 추정하고 있다.

**시사점** — 석탄 분진 발화 추정 속에서 잔불·인명 피해 여부와 발전소 재가동 시점이 여수국가산단 전력공급의 남은 관건이다.

[여수국가산단 내 화력발전소 화재…석탄 분진 발화 추정](https://www.donga.com/news/Society/article/all/20260822/134523770/1)

### ⚠ 태풍 오키나와 앞바다 접근…처서에도 폭염·소나기

태풍이 오키나와 앞바다로 접근 중인 가운데 22일 부산은 34도 폭염을 보이고 서울에는 소나기가 내렸다. 절기상 처서를 맞았지만 '처서 매직' 없이 무더위가 이어졌다.

**시사점** — 처서에도 무더위가 꺾이지 않고 태풍이 오키나와 앞바다로 북상 중이어서, 주말 남부 폭염과 태풍 진로가 이번 주 최대 변수다.

[날씨 '태풍경로→오키나와 앞바다 접근중' 부산 34도 폭염속 서울엔 소나기 - gukjen](https://news.google.com/rss/articles/CBMibkFVX3lxTFBJT0ZVbVh4RmlYdWF5Sk81S0NHQ1hQV3FaMV9ITDg5OHZvQVpzYUl2azFkV3ZydlpmWUFvaFZDVkd2Rms3SC0xa192QnRJa0NXZDRfXy1oMFN5UHFIYy0yeVlvSEtkWTRUZVpEUE9B?oc=5)

### 🆕 충남 아산호 인근서 70대 벼락 심정지…이송 중 맥박 회복

22일 오후 2시48분께 충남 아산시 영인면 아산호 인근 농로에서 70대가 벼락에 맞았다. 심정지 상태로 발견돼 심폐소생술을 받으며 병원으로 이송됐고, 이송 중 맥박이 돌아왔다.

[충남 아산호 인근서 70대 벼락 심정지…이송 중 맥박 돌아와](https://www.donga.com/news/Society/article/all/20260822/134523762/1)

### 제주 여성실종 담당 경찰 긴급체포…허위 종결 의혹

제주 30대 여성 실종 사건을 허위로 종결했다는 의혹을 받는 경찰관이 또 다른 실종 사건마저 허위로 종결한 정황이 드러나 긴급 체포됐다.제주경찰청은 22일 오후 3시 28분경 제주시 모처에서 제주서부경찰서 소속 경장을 직무유기, 공전자기록 위작·행사, 위계에 의한 공무집행방해 혐의로 긴급체포했다고 밝혔다.경찰에 따르면, 해당 경장이 담당했던 실종 사건이 실제 소재가 확인되지 않았는데도 7월2일 종결 처리한 사실이 뒤늦게 확인됐다. 이에 경찰은 21일 이 사건의 허위 종결 정황을 추가로 파악한 뒤 

[제주 여성실종 담당 경찰 긴급체포…허위 종결 의혹](https://www.donga.com/news/Society/article/all/20260822/134523816/2)

### 김민석, 90도 인사 논란에 “의미도 좋고 보기도 좋은 인사법 다듬어달라”

김민석 더불어민주당 대표와 한병도 원내대표를 비롯한 신임 최고위원들이 20일 국회에서 열린 의원총회에서 고개숙여 인사하고 있다. 박민규 선임기자더불어민주당 김민석 대표가 최근 민주당 의원들이 단체로 ‘90도 인사’를 한 것을 두고 일각에서 ‘과도하다’는 지적이 나온 데 대해 “의미도 좋고 보기도 좋은 단체인사법을 곧 다듬어 주리라 믿는다”고 밝혔다.김 대표···

[김민석, 90도 인사 논란에 “의미도 좋고 보기도 좋은 인사법 다듬어달라”](https://www.khan.co.kr/article/202608222004001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### [날씨] 전국 무더위 속 곳곳 소나기…수도권·강원 새벽까지 비 - 연합뉴스

[날씨] 전국 무더위 속 곳곳 소나기…수도권·강원 새벽까지 비    연합뉴스    [날씨] 내일 '처서 마법' 없어…한낮 33도 안팎 더위    v.daum.net    내일 새벽까지 중부 곳곳 비나 소나기…돌풍 천둥 번개 유의    KBS 뉴스    전국 곳곳 여름비…'낮 최고 31도' 무더위·열대야[내일날씨]    뉴시스    처서에도 무더위 계속···주말 전국 곳곳 비·소나기    경향신문

[[날씨] 전국 무더위 속 곳곳 소나기…수도권·강원 새벽까지 비 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE04LS03SjlPUEEwX1lVSWhWdC1xdFZ3dm1tclFHSmRoYmIyUXdfbHFhTG1iTGZWU2p1ZlBxYjB2Z2tzTE9RcmQ1RXZFX1N5ZC1SZzBHTkw1UDVQZ03SAWBBVV95cUxOM2syMmFlTjZackpXdS1uWENSamFHblV3MkowNXRoQVYxU0hJLWlDa3hveG9EVHlrTzhLbGV3QlVPWXFRblVRSzdobnhlVXdZZlhTOW80S2kyUGtGZFY0N28?oc=5)

### 美 미인대회 우승 일주일 만에 ‘왕관 박탈’…“뺑소니 혐의에 결혼 이력까지”

미국 미인대회 ‘미스 그랜드 USA’ 우승자가 왕관을 쓴 지 불과 일주일 만에 자격을 박탈당했다. 대회 측은 박탈 사유를 공개하지 않았지만 과거 결혼 이력과 뺑소니 혐의로 재판을 받고 있다는 사실이 알려지면서 논란이 일고 있다. 20일(현지 시간) 뉴욕포스트 등 외신에 따르면 미스 그랜드 USA 조직위원회는 전날 성명을 통해 2026 미스 그랜드 USA 우승자인 메킬라 리(27)의 임기를 종료하고 우승 타이틀과 관련된 모든 자격을 박탈한다고 밝혔다.주최 측은 “이번 결정은 미스 그랜드 USA 조직

[美 미인대회 우승 일주일 만에 ‘왕관 박탈’…“뺑소니 혐의에 결혼 이력까지”](https://www.donga.com/news/Inter/article/all/20260822/134523807/2)

### 제주 서귀포시 동쪽 79km 해역서 규모 2.7 지진…“피해 없어”

22일 오후 7시9분께 제주 서귀포시 동쪽 79km 해역에서 규모 2.7 지진이 발생했다.기상청에 따르면 지진 발생 위치는 북위 33.18도, 동경 127.41도다. 발생 깊이는 19㎞다.지진계에 기록된 최대 진도는 Ⅰ(1)이다. 대부분 사람은 느낄 수 없고 지진계에만 기록되는 수준이다. 기상청은 “지진 피해는 없을 것으로 예상된다”고 밝혔다.[서울=뉴시스]

[제주 서귀포시 동쪽 79km 해역서 규모 2.7 지진…“피해 없어”](https://www.donga.com/news/Society/article/all/20260822/134523803/1)

### KLPGA 챔피언십 3R 선두 서교림 “우승 기회 놓치지 않겠다”

서교림이 한국여자프로골프(KLPGA) 투어 시즌 두 번째 메이저 대회인 BC카드·한경 제48회 KLPGA 챔피언십(총상금 15억원) 셋째 날 선두를 수성했다.서교림은 22일 경기도 포천의 포천힐스 컨트리클럽(파72)에서 열린 대회 3라운드에서 보기 없이 버디만 3개를 잡으며 3언더파 69타를 작성했다.중간 합계 10언더파 206타를 기록한 서교림은 2라운드 공동 선두에서 단독 선두로 올라섰다.지난해 2차례 준우승하며 신인왕에 올랐던 서교림은 올해 6월 셀트리온 퀸즈 마스터즈, 인카금융 더헤븐 마스

[KLPGA 챔피언십 3R 선두 서교림 “우승 기회 놓치지 않겠다”](https://www.donga.com/news/Sports/article/all/20260822/134523798/1)

### 전쟁 6개월·경제난 심화에…이란 지도부 “전쟁 끝내야”

6개월째 이어지는 전쟁과 미국의 제재로 경제난이 심화하자 이란 지도부 내에서 전쟁을 끝내고 경제 회복에 집중해야 한다는 목소리가 나오고 있다. 21일(현지 시간) 월스트리트저널(WSJ)에 따르면 마수드 페제시키안 이란 대통령은 이날 “전쟁은 어느 시점에는 끝나야 한다”며 “지금 우리의 힘과 존엄성을 보여주고 세계에 우리가 승리했으며 전쟁을 끝내겠다고 말하는 것이 더 낫다”고 밝혔다.모하마드 바게르 갈리바프 이란 의회 의장도 경제 위기를 방치해서는 국가 안보를 확보할 수 없다고 강조했다.갈리바프 의

[전쟁 6개월·경제난 심화에…이란 지도부 “전쟁 끝내야”](https://www.donga.com/news/Inter/article/all/20260822/134523793/1)

### 제주 여성 실종사건 허위종결한 경찰관 긴급체포

제주 한림항에서 장미란씨로 추정되는 시신이 신분증과 함께 발견됐다. 이 실종사건을 허위로 종결한 경찰관이 긴급체포됐다. 경찰이 '연락됐다'고 한 통화 기록이 없고 실종시스템 기록도 삭제된 것으로 드러났다.

**시사점** — 통화기록·실종시스템 기록 삭제 경위가 향후 감찰과 초동수사 부실 수사의 핵심 쟁점이다

[[속보] 제주 여성 실종사건 허위종결한 경찰관 긴급체포 - 연합뉴스TV](https://news.google.com/rss/articles/CBMiZ0FVX3lxTE1Nbzk1elZER25jWFdIRHE0SUR1aXJZUExSSzVUTW5DWnFGWWZsWHl2QS1xUEhyRTRMbFNBWE5yTHdwRm1ZN2w4aDBJdVpRUkJ5NkV0NW1SdDB1SFFRU0JMT0VoSkhjOWc?oc=5)

### 🆕 캐리비안베이 여자탈의실 불법촬영 20대 남성 검거

용인동부경찰서가 캐리비안베이 여자 탈의실에서 불법 촬영을 한 20대 남성 A씨에게 구속영장을 신청했다. A씨는 지난달 중순과 30일 두 차례 워터파크에 침입한 혐의를 받는다.

**시사점** — A씨 구속영장 발부 여부와 워터파크 탈의실 보안 점검 확대가 관건이다

[캐리비안베이 여자탈의실 불법촬영 20대 남성 검거](https://www.donga.com/news/Society/article/all/20260822/134523839/1)

### 🆕 제주도산지 강풍주의보 해제…제주시서부 폭염경보 유지

제주도산지의 강풍주의보가 해제됐으나 제주시 서부에는 폭염경보가 유지된다. 처서가 지났지만 제주는 밤 최저기온 28.8도를 기록하며 더위가 이어지고 있다.

**시사점** — 밤 최저 28.8도 열대야가 주말까지 이어져 제주 냉방 수요가 지속된다

[제주도산지에 강풍주의보 해제…제주시서부에 폭염경보 유지 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE53YXBFSHU5T1M3NnRUX09tSVJRSXcwMVZ5UnZ4T2t0dDFiQ1NWakN5Wm1CVUFfSDlXZi03WnV4ODNYeDRrRDBmdktDZ2hCTFZKajFYZ3NiY3RmZkHSAWBBVV95cUxQeEVFaG4tdzRvUWJYcjZBZXRXRGt6YV9QV1ZNZWJteFdUUjU1VTBDdy15eEhpeHhJeGVJc29JellyQlRBVGE2blJOVHRYbk85dUVfcl83VFlBeTJINU1faVM?oc=5)

### 🆕 '우지원 딸' 우서윤, 미스코리아 진 당선

전 프로농구 선수 우지원의 딸 우서윤(22)이 제70회 미스코리아 선발대회에서 진으로 당선됐다. 서울 강남구 코엑스 오디토리움에서 열린 본선에서 서울·경기·인천 '선' 출신으로 왕관을 차지했다.

[‘우지원 딸’ 우서윤, 미스코리아 진 됐다](https://www.donga.com/news/Entertainment/article/all/20260822/134523836/1)

### 🆕 Z세대 사로잡은 '규칙괴담' 콘텐츠 인기

지켜야 할 규칙만 나열하고 위반 시 위험은 명확히 알려주지 않는 '규칙 괴담' 콘텐츠가 인기 장르로 자리 잡았다. 대놓고 무서운 장면 없이도 공포를 주는 형식이 특징이다.

[“7층 버튼 깜빡이면 내리십시오”…Z세대 푹빠진 ‘규칙괴담’ [트렌디깅]](https://www.donga.com/news/Culture/article/all/20260821/134520168/2)

### 🔴 집중호우 피해 엿새째…주말에도 복구 총력

지난 며칠간 지속된 집중호우로 인해 전남·경북 등지에 홍수와 산사태가 발생했다. 현재 복구 작업이 엿새째 진행 중이며, 주말에도 인력과 장비를 투입해 잔여 피해 복구에 총력을 기울이고 있다.

**시사점** — 주말까지 투입되는 1,200명 인력과 300억 원 예산이 복구 속도를 좌우한다.

[집중호우 피해 엿새째…주말에도 복구 총력 - KBS 뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTFB0QTdBY0ZuUTY4Z25BUWJFS1h0a2NJblYzUW9nMVNleExKdlRCRkoxb1F2aVJYdUtRcl9qSktSMDRMc2VaajNyWTlsbEhxMnZPeTJWVEJFNTFVUDQ?oc=5)

### ⚠ 중부지방 강타한 폭우에 피해 속출…화성 운평 하루 110㎜

22일 경기 화성시 우정읍 운평리에 하루 110㎜의 비가 쏟아지는 등 수도권과 강원·충청 등 중부지방 곳곳에 강한 비가 내렸다. 폭우 속에 여러 지역에서 각종 사고가 잇따르며 피해가 속출했다.

**시사점** — 처서를 앞두고도 중부 집중호우가 이어져 화성 등 피해 지역의 추가 강우와 침수 여부가 변수다.

[“화성 운평에 110㎜”…중부지방 강타한 폭우에 피해 속출](https://www.donga.com/news/Society/article/all/20260822/134523871/1)

### 🆕 제주항공 참사 600일…유해 1740점만 남아 “책임자 기소조차 안 돼”

12·29 제주항공 여객기 참사 600일을 맞아 유해 1740점만 수습된 상태로 남았다. 유가족은 책임자 기소가 이뤄지지 않았다며 무안군의회를 항의 방문했다.

**시사점** — 참사 600일에도 책임자 기소가 없어 유가족의 무안군·검찰 대응 요구가 계속된다.

[유해 1740점만 남은 ‘제주항공 참사’ 600일…“책임자 기소조차 안 돼” - 한겨레](https://news.google.com/rss/articles/CBMiYEFVX3lxTE1odEFyendLYWJhZDhKSlFFZGlKMGJYbTIyeXd4WWdKa3JoRmRpakxQTmllWXNSNElQSU5KQXhxVXAwZ2lrZmxJdzhGWHpEZHJuSWt0MFFyNGxKS25MVEZKaw?oc=5)

### 🆕 제주 여성 실종사건 허위종결한 경찰관 긴급체포…추가 사례 발견

제주 여성 실종사건을 허위로 종결한 경찰관이 긴급체포됐다. 가정폭력 신고 기록 삭제 등 추가 허위종결 사례도 발견됐다.

**시사점** — 허위종결 추가 사례가 나오면서 제주경찰의 실종·가정폭력 신고 처리 전반이 감찰 대상이 된다.

[제주 여성 실종사건 허위종결한 경찰관 긴급체포 - 경향신문](https://news.google.com/rss/articles/CBMiWkFVX3lxTE1GRTQ1ZkJXRTZPLXlLZU9vbDhPYkktOUNaUkV5THR5Vzh0eDF5cUFRcnNaZ1N5QU8xckMtTm4wOHBWZHpsbHFYOGhBeUVNR3BrYW4teEdiMmlrd9IBX0FVX3lxTE0zTVp2ZHRzdnFURTVvVDRUNENwOHZNRTJwRmFOU3NWUTB1RVRxVkpKMTh0NHpQNG5sYWJ0Sy1iWnA3ZkhoXzhYSGV3ZzE1MWNWSTY0ZFUyV2VPMXBYVVBj?oc=5)

### 🆕 워터파크 여자탈의실에 가발 쓰고 침입해 몰카 찍은 20대 체포

숏컷 가발을 쓰고 여장한 20대 남성이 캐리비안 베이 여자탈의실에 침입해 불법촬영을 하다 적발됐다. 경찰에 체포됐다.

[워터파크 女탈의실에 가발 쓰고 들어가 몰카 찍은 20대 - 조선일보](https://news.google.com/rss/articles/CBMihgFBVV95cUxPd1hGZWF5ZlJKQzNCdEJ3Xy1rSmVFc0M0QTRWdTlFNTJWSlhES2NXWU1Wc1ZiWWVnYnoyRlNNWUhJNXdfa2VRZExVZVdyY2YtcmNfZEdvSW1pRERSWHlaMzYxWml6U3VzYndELTZQc0I5Y2gwM0hKaEJMZnZRbWFUYlQ2RFdTQQ?oc=5)

### 🆕 ‘장미란씨 실종’ 담당 경찰 긴급체포…허위 종결 사건 또 있었다

제주에서 실종됐던 장미란씨로 추정되는 시신이 한림항 인근에서 신분증과 함께 발견됐다. 실종 사건을 담당한 경찰관이 긴급체포됐고, 또 다른 허위 종결 사건도 있었던 것으로 드러났다.

**시사점** — 긴급체포된 담당 경찰관의 허위 종결 사건이 몇 건 더 있는지가 제주경찰 부실 수사 논란의 관건이다.

[‘장미란씨 실종’ 담당 경찰 긴급체포…허위종결 사건 또 있었다 - 한겨레](https://news.google.com/rss/articles/CBMickFVX3lxTE9PWGt4TFlsVjk4Nnp2Q0FjMlItUDZBZlF5TTVHY2tYeEFyZ0ZxaEZaYTN0bmEtQmVYMFRodHRWWk5fTkdtSjFoT1RBLUVhaFdiOUdxY01FZHdvZ3B0bFlIMUZYeWphS0NWQzRmLUowdnpKQQ?oc=5)

### 거제·통영 주말에도 수해복구 총력전…이틀간 4800명 투입

기록적 집중호우로 피해를 입은 거제·통영에서 주말에도 수해복구 작업이 이어진다. 경남도에 따르면 22~23일 이틀간 인력 4824명과 장비 516대가 투입된다.

**시사점** — 주말 4824명·장비 516대 투입 규모가 이번 수해 복구 속도를 가른다.

[거제·통영 주말에도 수해복구 총력전…이틀간 4800명 투입](https://www.donga.com/news/Society/article/all/20260822/134523881/1)

### 🆕 여수 화력발전소서 화재…6시간 만에 완진

전남 여수산단 한국남동발전에서 자연발화로 추정되는 화재가 발생했다. 화재는 약 6시간 만에 완진됐으며 석탄 공급에는 지장이 없는 것으로 파악됐다.

**시사점** — 완진됐으나 자연발화 원인 규명과 재발 방지가 한국남동발전의 남은 과제다.

[여수 화력발전소서 화재…진화까지 장시간 예상 - 경향신문](https://news.google.com/rss/articles/CBMiWkFVX3lxTE10TTVYRUZlQ3dIUHJROUpmTWxQQXd0OVZsbmlfQ0F5UG5tZVRidUQtbzR1N2dkMXZHcU5aMzlSNjJzc2tkdEg2SXZzc2JtbXZxbllidHJHTHBzd9IBX0FVX3lxTE1wN2lVNGJjZXBvbzliZlVBTE45LXV5MzlkSFp2dTdxZGo1LWdEaURjTWF6OU83MG1hMXFpZDdvajlOcGk3ZVZfM1FBX2hnOWc1MEtKSW13VmtRNTRvd2U4?oc=5)

### 🆕 충청 휩쓴 비바람…아산서 70대 낙뢰 맞아 심정지

충청 지역에 비바람이 몰아치면서 충남 아산에서 70대 남성이 낙뢰를 맞아 심정지 상태로 이송됐다. 이송 중 맥박이 돌아왔으며 강풍 피해도 잇따랐다.

**시사점** — 아산 등 충청권 강풍·낙뢰 피해가 이어져 추가 인명·시설 피해 여부가 변수다.

[충청 휩쓴 비바람…벼락 맞은 70대 중상 - 조선일보](https://news.google.com/rss/articles/CBMihgFBVV95cUxQYzN3SnJpZFFaTjRXSnBPRm85MWI1OWlPaE10bHJsNHFxVkNFQmhod2xNanE4SlBNNEtSN0RERnJ2bllqRUFBZm5KMTBwLVRiTHRRMFJGbkJibmVFenlBRkY5Wk8td2VoeDNxeFliOGhKX2Uwbkh1T1B3ekxCTTh1bERNUFFJdw?oc=5)

### 🆕 최태원 이혼이 소환한 '노태우 비자금'…검찰 강제수사 착수

최태원 회장의 이혼 재판 과정에서 불거진 '노태우 비자금' 의혹에 검찰이 강제 수사에 착수했다. 검찰은 압수물을 분석하며 '152억 기부금'을 주목하고 있다. 노소영 측이 제시한 '300억 메모'로 재산 몰수 가능성이 거론된다.

**시사점** — 검찰의 압수물 분석과 '152억 기부금' 성격 규명 결과가 재산 몰수 여부를 가른다

[최태원 이혼이 소환한 ‘노태우 비자금’… 검찰, 강제 수사 착수 - 조선일보](https://news.google.com/rss/articles/CBMihwFBVV95cUxOeDBEUW5Ubk5qRHNiZ0FFV29xeG5mbzJJbWtEVldCVzgzLTNDaEw1UDFtQ1BfSUVEUnlBTlYyZndzZXBHUFFVd1l2MWhQXzBZanJKX2Vock5BY0J4MTdRT2E0UVh0c1dtV24zV2p0akw1Y0Nqb0JNNmE1LWF1dmlZRW5rTy0wQjg?oc=5)

### 🆕 안세영, 세계 3위 왕즈이 꺾고 세계선수권 결승 진출

세계랭킹 1위 안세영이 22일 인도 뉴델리에서 열린 2026 BWF 세계선수권 여자 단식 준결승에서 세계 3위 왕즈이(중국)를 꺾고 결승에 올랐다. 안세영은 3년 만의 세계선수권 정상 탈환에 한 걸음만 남겨뒀다.

**시사점** — 결승 승리 시 안세영은 3년 만에 세계선수권 정상을 되찾는다

[‘셔틀콕 여제’ 안세영, 세계 3위 왕즈이 잡고 세계선수권 결승 진출](https://www.donga.com/news/Sports/article/all/20260823/134523894/1)

### 🆕 김상식의 베트남, '동남아 월드컵' 결승 1차전서 태국 2-0 제압

김상식 감독이 이끄는 베트남 남자 축구 대표팀이 22일 태국 방콕 원정 결승 1차전에서 태국을 2-0으로 이겼다. 베트남은 '동남아 월드컵'으로 불리는 2026 아세안 현대컵 2연패 가능성을 높였다.

**시사점** — 1차전 2-0 승리로 베트남이 아세안 현대컵 2연패에 다가섰고 2차전 결과가 남았다

[김상식의 베트남, 동남아 월드컵 결승 1차전서 태국 2-0 제압](https://www.donga.com/news/Sports/article/all/20260823/134523900/1)

### 🆕 아파트 경리가 관리비 440억 횡령 의혹…20년간 아무도 몰라

한 아파트 경리가 관리비 약 440억 원을 횡령한 의혹이 제기됐다. 장부에는 '정상 납부'로 기록돼 20년간 주민들이 알지 못했다.

**시사점** — 주민들이 20년간 낸 관리비 440억 원의 회수 가능 여부가 관건이다

['440억 원 횡령' 의혹 장부엔 '정상 납부'...수십 년간 아무도 몰라 - KBC광주방](https://news.google.com/rss/articles/CBMiYkFVX3lxTE82VG1OT0hOYmdkYlhpR1FwdGh6M0JmYTk4VmVlZjllazl1Y3NCWG1vX05PM0pzZU5qWDdvdmxYbEN2V0U1SUo3RDFJbjhQSnQ0R3M0Q3owbnU4TGhOLVdIaml3?oc=5)

### 🆕 연세대 산책로 '복면 성추행' 재발…산책로 폐쇄·순찰 강화

연세대 산책로에 복면을 쓴 남성이 다시 출몰해 성추행 사건이 발생했다. 학교는 산책로를 폐쇄하고 순찰을 강화했다.

**시사점** — 학교가 산책로를 폐쇄했고 반복 출몰한 용의자 검거 여부가 남았다

[[현장] 복면 알몸남 또 출몰 연대 산책로, 가로등 옆은 칠흙 같은 어둠 [세상&] - v](https://news.google.com/rss/articles/CBMiRkFVX3lxTE1OMTRiSHFfR3Jfd3BHUjJGYUpBaFMya0V3OUhTajgwYm9LXzZuT2FYMmJkM0REUXZRSTMySHdWbUZqTjhEMXc?oc=5)

### 4편, '선거에 중국이 개입했다'는 주장, 사실인가 - 뉴스타파

4편, '선거에 중국이 개입했다'는 주장, 사실인가    뉴스타파    행실본.‘현행 선거 100% 수 개표, 가짜 '투개표 조작설' 음모론에 의해 보수 궤멸 중    뉴스에이    "한국교회, 선거 허위정보 경계하고 사실·진실 분별해야"    자유일보    [社說] 선거 개입 논란, 주권의 경계는 어디인가    월드투데이    논점 흐린 부실·부정 선거 따지기 "이번 지방선거는 위헌·위법 선거"ㅣ허민의 정치카페 [문화일보]    문화일보

[4편, '선거에 중국이 개입했다'는 주장, 사실인가 - 뉴스타파](https://news.google.com/rss/articles/CBMiSkFVX3lxTFA1TDU3Qi16REI5NkVtWEpKZ0lFblFnNm5qUFZkSC0zVXBaRDVZRGZEdmRnRzNmYUNkOTFTT3hGRnpiYU8wMG1TRXZB?oc=5)

### [단독] 양평군청 출신 60대 전 간부, 자택서 심정지 상태 발견 뒤 숨져 - 경기일보

[단독] 양평군청 출신 60대 전 간부, 자택서 심정지 상태 발견 뒤 숨져    경기일보

[[단독] 양평군청 출신 60대 전 간부, 자택서 심정지 상태 발견 뒤 숨져 - 경기일보](https://news.google.com/rss/articles/CBMiW0FVX3lxTFBZaE92Tl9UNURnYkcySFQ1MjRiNll0bUNxRDNjd1RPdnFNYzlPVXVtWmZtQzRsTThnT0Y3bWlPSXVJaV9laHZtb2ZsR0VEa3dlSW53U1ZrMV9rZFk?oc=5)

### “전 연인들과 성관계 했어?… 죽이겠다” 과거 추궁에 장모 협박까지 한 30대… - 문화일보

“전 연인들과 성관계 했어?… 죽이겠다” 과거 추궁에 장모 협박까지 한 30대…    문화일보    "대답 안하면 반려동물 죽이겠다" 아내 감금·협박한 30대…징역 2년    경기일보    "죽이겠다" 아내 14시간 감금…의처증 30대, 징역 2년    뉴시스    전 연인들과 성관계 여부 추궁…아내 인정하자 30대가 한 짓    매일경제    "전 연인들과 성관계 했어?" 아내 과거 추궁·장모 위협한 30대 실형    매일신문

[“전 연인들과 성관계 했어?… 죽이겠다” 과거 추궁에 장모 협박까지 한 30대… - 문화일](https://news.google.com/rss/articles/CBMiUEFVX3lxTE1DaGkzZVJRdmotMW5lRDNZa29VZXB1QTQzYkFDb053c01RaDFDUUt0YjNVSU5EeEQwRWlGQVZVb3NmOVJhOExvY25QZ2o3M3l0?oc=5)

### 🆕 ‘숏컷 가발 위장’ 물놀이장 여탈의실 불법촬영 20대 남성 검거

가발을 쓰고 여성 탈의실에 들어가 불법촬영을 한 20대 남성이 도주 22일 만에 검거됐다. 경찰은 이 남성에 대해 구속영장을 신청했다.

**시사점** — 신청된 구속영장의 법원 심사 결과가 다음 절차다

[‘숏컷 위장’ 터파크 女탈의실 불법촬영…20대 남성 검거 - 연합뉴스TV](https://news.google.com/rss/articles/CBMiZ0FVX3lxTE5ibGVGUUFGQ2FFYXR2ZUhDR1E1c0YyM2hqM2k3TE02VHg5ZWxkT1pmZmJDWXVrdWxEMFBpNk9NV29YR3A0MTk4N3dqcVp1YWdRN0haNGxwa0MxZDdJbmhnRVZUWmI3LTg?oc=5)

### 🆕 불교 민주화운동 앞장선 명진스님 입적…제주 해양사고

불교계 민주화운동과 사회참여에 앞장선 명진스님이 22일 입적했다. 세수 76세, 법랍 52년으로, 제주 서귀포 해양사고(프리다이빙 중 사고)로 숨졌다. 올해 제적 9년 만에 승적을 회복해 종단과의 갈등을 마무리한 직후였고, 이 대통령이 애도를 표했다.

**시사점** — 올해 승적 회복으로 종단과 9년 갈등을 끝낸 직후여서, 종단 차원의 장례 규모와 절차가 관전 포인트다.

[봉은사 주지 지낸 명진스님 입적…프리다이빙 중 사고 - 한국경제](https://news.google.com/rss/articles/CBMiWkFVX3lxTE1Mek5GaFpqM1MxOHpHd2tlLUR5RV9VWGZyMnQ2eE1DdXA0ZXBaWmFENHo2MmxnUkFQR0tSZ1MwQkQ1cXBEQXY4TDdPNW9JTXAtT0tSNFZVWjlwUQ?oc=5)

### ⚠ '처서 매직' 없이 무더위 지속…낮 최고 35도, 곳곳 소나기

처서를 앞두고 선선해지는 '처서 매직' 없이 무더위가 이어진다. 낮 기온은 31∼35도로 예보됐고, 오후부터 곳곳에 소나기가 내리겠다. 부산·경남은 23일 낮 최고 33∼36도로 무더위가 계속된다.

**시사점** — 낮 최고 35도 무더위가 처서 뒤에도 이어져 온열질환 경보와 냉방 전력수요가 관건이다.

[선선한 ‘처서 매직’ 없다…낮 최고 35도 무더위 속 소나기 - 한겨레](https://news.google.com/rss/articles/CBMibEFVX3lxTE1qSVJwRl9zVmtHWlFyak1PSjRUaGw3WHo0a3hnMFZnMVBiamRXZVJkT2stNjRzaE5zc1ptSlEyZ2pSeVZjZUZLQVRBdjk2T1ZTeTE2TGlLbXBYeDdnQUN1WUFTUHp4V3JkdnJTcw?oc=5)

### 🔴 제18호 태풍 사우델 경로 24시간 전보다 서쪽…강도 3 발달

제18호 태풍 사우델이 전해상에서 서쪽으로 이동하면서 강도가 3단계로 강화되고 있다. 기상청은 동해안과 남해안에 강풍·호우를 예고하고 있다. 현재 해안 지역은 항만·어선 운영에 차질이 발생할 가능성이 있다.

**시사점** — 동해안 연안 어민과 항만 운영이 8월 말까지 태풍 경로 변동에 따라 큰 영향을 받을 가능성이 있다.

[제18호 태풍 사우델 경로 24시간 전보다 서쪽…강도 3 발달 - 톱스타뉴스](https://news.google.com/rss/articles/CBMickFVX3lxTE11RzlBOWJ6U0h3OV9MekZnVW1zSW84cXBQbGt3R2kzNGFua202c2FYTFpvbXdXWU9QdzFERENxYzhnQnYtdWRwN09VWHRWNnJBWUNVMzc1dU53UmNRUktUdk00X0N6STVibW43ZXZCM2VZUQ?oc=5)

### ⚠ 제주, 폭염 특보에 높은 습도…최고 체감 온도 35도 이상

제주에 폭염 특보가 발효되었으며, 습도가 높아 체감 온도가 35도 이상으로 기록되고 있다. 기상청은 오늘 밤까지도 높은 온도가 지속될 것으로 전망하고 있다. 지역 보건당국은 열사병 예방 조치를 권고하고 있다.

**시사점** — 제주 관광업계와 야외 근로자는 8월 22일까지 체감 온도 35도 이상 지속에 대비해 물 공급 및 응급 의료 체계 강화가 필요하다.

[제주, 폭염 특보에 높은 습도…최고 체감 온도 35도 이상 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTFBLYVpOek02SDlfVWtORWFxS0ozTHJIM1dhR1lMVjk0T2J4T2h3ejRWb1dXYmgwX0E0YmgzQjE5TTV2UmRFTUZMU25USXJvZUFIMVJWclQySVp4bTTSAWBBVV95cUxPRzNfc1dMSXVWOWRkMkJnUXB1Wk1LaUpXczZCc0R5b2VRWkhZdmt1WVc2UzQ1cTJZOGpBWDg1RDE4blNTTFctRV9DVWJvc2UyTTJmLUJ4YnVTNUk0bHFJU3o?oc=5)

### 🆕 봉은사 주지 지낸 명진스님 입적…제주서 프리다이빙 사고

불교계에서 영향력 있던 명진스님이 입적하였다. 같은 날 제주에서 프리다이빙 중 사고가 발생해 1명이 사망했다. 두 사건이 동시에 보도돼 종교계와 지역 사회에 큰 충격을 주고 있다.

**시사점** — 불교계 신도와 제주 지역 다이빙 업계는 명진스님 입적과 사고로 인해 향후 의식 및 안전 규정 검토가 요구된다.

[봉은사 주지 지낸 명진스님 입적…제주서 프리다이빙 사고 - 동아일보](https://news.google.com/rss/articles/CBMidkFVX3lxTE1QVlRNczdKTW9EOVdfeVU5VlYxeFlxa2N3UnRpT3NJNERMVWFoVS1VS3lmakRRWDd1SWFMX3hfY0VNaWUyQ0QzMkliY1Q2UWh5Vkx6VkdCM2Q5d1BLWnM3NVlNcE9vV0pUU0luVjBoenNtV01PSHfSAWZBVV95cUxOMzNIY0xjdTg1QmhMcFIzWWF4cUhuVUxwSEs2WFd4QjNuMHZoajVuT1oxUGdhOU10cnRRUENsVGpDSW5JQS1Pb0RyazJ5aWtxbmJWS25GLVBVdkdlX00wZzNhWnlBX1E?oc=5)

### 🆕 천안서 부모 흉기 살해·중상 입힌 10대 외국인 검거

충남 천안 목천읍의 한 아파트에서 10대 외국인 A군이 40대 부모를 흉기로 찔러 아버지가 숨지고 어머니가 중상을 입었다. 천안동남경찰서는 존속살인 혐의로 A군을 붙잡아 조사하고 있다. A군은 부모의 다툼을 말리다 흉기를 휘두른 것으로 조사됐다.

**시사점** — 존속살인 혐의로 조사 중인 A군의 체류 신분과 어머니의 상태, 이후 재판 진행이 남은 쟁점이다.

[흉기로 부모 찌른 10대 외국인···아버지 숨지고 어머니 중상](https://www.khan.co.kr/article/202608231009001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 현대차그룹, 경남 수해 복구에 성금 10억원…세탁구호차량 급파

현대자동차그룹이 집중호우로 큰 피해를 본 경남 거제·통영 등 수해 지역에 성금 10억원을 희망브리지 전국재해구호협회에 전달했다. 세탁구호차량도 급파했으며, 침수 차량 수리비는 최대 50%까지 감면 지원한다.

**시사점** — 성금 10억원과 침수차량 수리비 최대 50% 감면은 거제·통영 수해 주민이 실제 신청할 수 있는 지원이다.

[현대차그룹, 경남 호우 피해 복구 성금 10억원 기탁…세탁구호차량도 급파](https://www.khan.co.kr/article/202608230923001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 경기도, 전세사기 피해주택 수리·안전관리비 최대 2000만원 지원

경기도가 임대인 연락 두절 등으로 관리가 어려운 전세사기 피해주택에 안전관리·유지보수 비용을 지원한다. ‘전세사기 피해주택 긴급관리 지원사업’ 하반기 신청은 오는 26일부터 다음 달 30일까지 받는다.

**시사점** — 신청은 26일부터 다음 달 30일까지이며, 임대인 연락두절 피해주택 소유·거주자가 최대 2000만원을 받는다.

[경기도, 전세사기 피해주택 수리비 등 최대 2000만원 지원](https://www.khan.co.kr/article/202608230956001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 당진, 고용위기 선제대응지역 지정…충남도 철강 노동자 지원 강화

충남 당진시가 ‘고용위기 선제대응지역’으로 1년간 지정됐다. 충남도는 기존 철강산업 위기 노동자 지원사업과 정부의 고용·전직·생계 지원을 연계하고, 내년도 국비 확보에 나서기로 했다.

**시사점** — 1년 지정 기간 철강 노동자 훈련·생계 지원 규모와 내년도 국비 확보액이 당진 고용 충격 완화의 관건이다.

[“철강 고용 충격 막는다” 충남도, 당진 ‘고용위기 선제대응지역’ 지원 강화](https://www.khan.co.kr/article/202608230953001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### ⚠ 보령 해상서 카약 전복·고무보트 침수…레저객 9명 전원 구조

주말 사이 충남 보령 해상에서 카약이 표류·전복되고 고무보트가 침수되는 등 해양사고가 잇따랐다. 보령해양경찰서는 레저활동객 9명을 전원 구조했으며, 기상 악화 시 해양레저 자제를 당부했다.

**시사점** — 주말 레저객 9명이 전원 구조됐으나, 기상 악화 주말의 해양레저 안전이 반복 변수로 남는다.

[[영상]카약 전복되고 고무보트 침수···보령 해상서 해양사고 잇따라](https://www.khan.co.kr/article/202608230931001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 수원 광교 하천변 나일왕도마뱀, 수색 11일 만에 포획

수원 광교신도시 산책로와 하천변에 출몰해 주민을 불안하게 한 70㎝ 길이의 나일왕도마뱀이 수색 11일 만에 포획됐다. 수원시와 소방 당국 등은 22일 오전 광교 홍재도서관 인근 하천변에서 뜰채로 도마뱀을 붙잡았다.

**시사점** — 11일간 광교 주민을 불안하게 한 70㎝ 개체가 포획돼, 유기·사육 경위 조사가 남았다.

[수원 광교 도심서 수색 11일 만에 나일왕도마뱀 뜰채로 포획](https://www.khan.co.kr/article/202608231019001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 ‘우지원 딸’ 우서윤, 제70회 미스코리아 진 선발

전 프로농구 선수 우지원의 딸 우서윤(22)이 미스코리아 선발대회에서 최고 영예인 ‘진(眞)’을 차지했다. 22일 서울 강남구 코엑스 오디토리움에서 열린 제70회 미스코리아 본선에서 서울·경기·인천 ‘선’ 출신으로 진에 올랐다.

[‘우지원 딸’ 우서윤, 미스코리아 진(眞) 됐다](https://www.donga.com/news/Society/article/all/20260823/134524217/2)

### ⚠ '매우 강' 태풍 사우델 오키나와로 북상…다음 주 한반도 영향 변수

태풍 사우델이 '매우 강' 세력으로 오키나와를 향해 북상 중이며, 경로가 남쪽으로 조정됐다. 다음 주 우리나라 날씨의 주요 변수로 지목된다.

**시사점** — 다음 주 한반도 날씨 변수인 태풍 사우델의 오키나와 남쪽 경로 조정 여부가 직접 영향 규모를 가른다.

[태풍 사우델, 오키나와 경로 남쪽으로 조정...한반도 영향은? - 데일리안](https://news.google.com/rss/articles/CBMimAJBVV95cUxOYUxGRlBVbl9LQVE2cUxEWkJmVHZmT250eDBoWkQ5UTU4OG5KUjlRdHlZMndYVFR5YlRKb0dVeS0xM3Y4ZDBaWFRDUDlKRVFpUWlQX0wtWU45Skg5cDVnaXh2V3lIOE1TTnotQmdscHRNaEEtMDh4VmRLRG1zc2pjZUxsdUlXSV9fSWdETG1US1owY0JvTzROZTVOeG5HallxNWZMYWtZa0hncVM5VUZvaGY4UHlhc0t2RlJYcUJHYzROaGZTN0YwMW00XzVsMVdKV0hYZnN2SnlWOEttNnpkNHdaZlAtVE0xWjZYU3JtVUNSTmd5MEtnYzFDaDlDeDM2Q0h6Y3UxV21mVGZsemRPR3lrU1p6RE5C?oc=5)

### 🆕 제주 실종자 51일 만에 숨진 채 발견…경찰 '임의 종결 수사' 추가로 드러나

제주에서 실종됐던 남성이 51일 만에 숨진 채 발견됐다. 경찰이 '무사하다'며 유족을 속인 정황에 더해 임의로 수사를 종결한 사례가 추가로 확인됐다.

**시사점** — 51일 만에 주검으로 발견된 사건에서 경찰의 임의 종결 수사가 추가로 드러나 유사 부실수사 감찰 범위가 확대될지 주목된다.

[제주 실종자 51일 만에 숨진 채 발견···경찰관 ‘임의 종결 수사’ 더 있었다 - 경향신](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9sSURyWVlRSVViMFNKenlLcm52TzRDTG1lRUN3Q2ZxdVBWY1lGcGN0LW1sZUYwZWF2OUwwYmZLSEpLVGQtVDgzXzktQzViTVRiTVE5R2VldVNKd9IBX0FVX3lxTE1SVXdaX1VzZHJqX0JaLVQ0VllMbnNIcmJkOHhvdlh4cEJIaUtDYWZCXzYxWktGXy1JZUtNdUxiT3pHMUg5UUpRRHFTOTctN1lzSjJTUHBvdm5aOGtZQzVz?oc=5)

### 🆕 국세청 전수조사…고가 법인주택 10채 중 4채가 '황제사택'

국세청이 고가 법인주택을 전수조사한 결과 10채 중 4채가 사주일가 거주 등 사적 용도로 쓰인 '황제사택'으로 나타났다. 국세청은 적발 법인에 대해 세무조사에 착수하고 법인자금 횡령 여부를 검증한다.

**시사점** — 국세청이 세무조사와 법인자금 횡령 검증에 착수해 적발 법인의 추징 규모와 조사 대상 확대 여부가 관건이다.

[직원 몰래 ‘한강뷰’ 최고급 아파트 사서 자녀 주거지로···‘황제사택’ 무더기 적발](https://www.khan.co.kr/article/202608231044001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 환율 하락·증시 변동성에…달러·금·예금으로 자금 이동

원·달러 환율이 1300원대로 하락하고 국내 증시 변동성이 커지면서 금·달러 등 안전자산과 정기예금으로 자금이 이동하고 있다. 반면 위험자산인 주식으로 향하는 자금은 줄고 있다.

**시사점** — 환율 1300원대 진입 후 금·달러·정기예금으로의 자금 이동이 이어져 증시 자금 이탈 규모가 주시할 변수다.

[‘환율 하락·롤러코스피’에 달러·금·예금으로 몰리는 돈](https://www.khan.co.kr/article/202608231049001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 전북, 전국 첫 'AI 교육 가이드라인' 제정…생기부 활용 전면 배제

전북교육청이 전국 처음으로 'AI 교육 가이드라인'을 제정해 9월부터 일선 학교에 적용한다. 과제·평가에 AI를 활용하면 범위와 목적을 표시하도록 하고, 생기부 활용과 딥페이크는 금지한다.

**시사점** — 9월부터 전북 일선 학교에 적용돼 생기부·평가 AI 활용 표시 의무가 다른 교육청 가이드라인의 기준점이 된다.

[학교 파고든 AI…전북 “생기부 활용 전면 배제”](https://www.khan.co.kr/article/202608231120001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 '두쫀쿠' 열풍 반년 만에 급랭…재료 수입량 90% 넘게 급감

지난해 말부터 올해 초 품귀까지 벌어졌던 '두바이 쫀득 쿠키(두쫀쿠)' 인기가 반년 만에 확연히 꺾였다. 원재료 수입량 등이 반년 만에 90% 넘게 급감한 것으로 통계에 나타났다.

**시사점** — 재료 수입량이 반년 만에 90% 넘게 급감해 두쫀쿠에 투자한 카페·수입업체의 재고 손실이 다음 변수다.

[오픈런 해도 품절됐던 ‘두쫀쿠’ 이젠 발길 뚝···재료 수입량 등 반년 만에 90% 넘게 ](https://www.khan.co.kr/article/202608231055001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 수원 광교 도심 대형도마뱀, 수색 11일 만에 포획

수원 광교 도심에 출몰해 주민들을 공포에 떨게 한 70㎝ 크기의 나일왕도마뱀이 수색 11일 만에 뜰채로 포획됐다.

**시사점** — 11일간 주민 공포를 부른 대형 파충류가 포획돼 유기·탈출 경위와 사육 관리 책임 규명이 남았다.

[수원 광교 도심서 수색 11일 만에 나일왕도마뱀 뜰채로 포획 - 경향신문](https://news.google.com/rss/articles/CBMiWkFVX3lxTE02QTlCd3phNnVRUUhJczJaQVRMQ3VnOWxfSlZKNjlqVDc1X2UzMWpEemM3bU1JNHNWRU10TVhnd01OeWNoTGFLMmxpaEFSc3lBR2NiM0RrU2k3QdIBX0FVX3lxTE1fNlplVFgzV1VIRWd3c2dyYkdQeEZzTkV3WlFpS1BJQ3VGMC0tRWVyQWxKbVY0blV1OUJ3Z2c1QWFQeVowYzgzaVd2N21BODl2NjZ1WUJWYmNjOWNMM0JZ?oc=5)

### 🆕 고가 법인주택 42%가 사주일가 ‘황제사택’…국세청 첫 전수점검

국세청이 고가 법인주택을 처음으로 전수 점검한 결과, 임대·업무용을 뺀 40% 이상이 사주 일가가 거주하거나 사적으로 쓰는 ‘황제사택’으로 나타났다. 한강 조망권을 갖춘 강남·용산 초고가 아파트를 사주 자녀에게 무상 제공한 사례도 확인됐다.

**시사점** — 첫 전수점검인 만큼 40% 이상으로 지목된 사주 일가 사택이 향후 과세·환수 대상이 될지가 관건이다.

[“회사 집이 회장님 집”…고가 법인주택 42% 사주일가 ‘황제 사택’](https://www.donga.com/news/Economy/article/all/20260823/134524650/1)

### 🆕 ‘실종사건 허위종결’ 파문…홍석기 국수본부장 제주경찰청 사과 방문

제주 30대 여성 실종사건 수사에서 ‘허위 종결’이라는 구조적 문제가 드러났다. 홍석기 경찰청 국가수사본부장은 23일 제주경찰청을 찾아 약 2시간 수사회의를 주재하고 사과의 뜻을 전했다.

**시사점** — 국수본부장 사과 이후 제주경찰청 재수사 결과와 관련자 문책 범위가 다음 관전 포인트다.

[‘실종사건 허위종결‘ 파문 국수본부장 제주행…“빈틈없는 수사” 주문](https://www.donga.com/news/Society/article/all/20260823/134524594/1)

### ⚠ 고유가 피해지원금, 31일 자정까지 써야…미사용분 소멸

행정안전부는 고유가 피해지원금을 오는 31일 자정까지 써야 한다고 23일 안내했다. 신용·체크카드 기준 3조5492억원이 지급돼 3조4542억원(97.3%)이 사용됐다.

**시사점** — 지급액 중 미사용 약 950억원이 8월 31일 자정 이후 소멸하므로 카드 사용자는 잔액을 확인해야 한다.

[“고유가 피해지원금, 31일까지 꼭 사용하세요”](https://www.khan.co.kr/article/202608231200011/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 중소기업 79% “납품대금 지급기한, 30일 이내로 단축이 적정”

중소기업중앙회가 수·위탁 거래 중소기업 500곳을 조사한 결과, 10곳 중 8곳이 현행 60일인 법정 납품대금 지급기한을 30일 이내로 단축하는 것이 적정하다고 답했다.

**시사점** — 정부가 60일 지급기한 단축을 추진하면 응답 기업 79%가 원한 ‘30일’이 입법 논의의 기준선이 된다.

[중소기업 79% “납품대금 지급기한, 60→30일 이내 단축이 적정”](https://www.khan.co.kr/article/202608231211001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 BTS·불닭이 연 273조 ‘K-에브리씽’…“생태계 구축 시급”

K팝·영화 등 콘텐츠에서 시작된 K컬처 열풍이 음식·뷰티 등 경제 전반으로 확장하며 연 273조 규모의 ‘K-에브리씽’ 시대를 열고 있다. 다만 하청기지 전락을 막을 생태계가 시급하다는 지적이 나온다.

**시사점** — 273조 시장에서 부가가치를 지키려면 하청기지 전락을 막을 생태계 정책이 다음 과제로 지목된다.

[BTS·불닭이 연 273조 ‘K-에브리씽’…“하청기지 전락 막을 생태계 시급”](https://www.khan.co.kr/article/202608231145001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=total_news)

### 🆕 ‘갑질 감수성’ 3년째 하락…폭언·모욕에도 무뎌진 직장인

시민단체 직장갑질119가 6월 1~9일 직장인을 조사한 결과, 폭언·모욕·반말 등 명백한 갑질에도 문제의식이 3년째 낮아졌다. 사적 심부름이나 반성문 강요에 대한 인식도 4년 전보다 약해졌다.

**시사점** — 갑질 감수성이 3년째 떨어진 만큼 근로감독과 직장 내 괴롭힘 제도의 실효성 점검이 요구된다.

[폭언·모욕에도 무뎌진 직장인들…‘갑질 감수성’ 3년째 하락](https://www.donga.com/news/Society/article/all/20260823/134524714/1)

## 한국 정치

**오늘의 분석**

다음 주 정기국회 개회를 앞두고 여야가 각자 진용을 다지는 한 주다. 이재명 대통령은 25일 민주당 신임 지도부 만찬과 28일 소속 의원 전원 오찬으로 당청 결속을 굳히고, 국민의힘은 27일 연찬회에 박근혜 전 대통령을 공식 초청하며 지지층 결집을 노린다. 같은 시기 김민석 대표는 당 자체 TV 개국을 지시하고 부동산 세제 개편의 보완을 요구하는 등 원내외 발신을 넓히고 있어, 대통령과 당 지도부, 원내가 한 방향으로 움직이는 민주당의 밀집 대형이 뚜렷하다.

이 결속의 이면에는 사법·검찰을 둘러싼 전선이 놓여 있다. 노웅래 전 의원의 항소심 무죄와 이 대통령의 사과를 두고 국민의힘은 "검찰 무력화", "사법 방탄"으로 규정했다. 다만 무죄는 법원의 판단이고, 개별 사건 하나를 곧바로 제도 후퇴로 등치하기는 이르다. 검찰 권한을 통째로 걷어내는 방식이 능사가 아니듯, 특정 판결을 정치 방패로 삼는 해석 역시 사건의 사실관계와 떼어 볼 필요가 있다. 진영이 서로의 프레임으로만 맞서는 구도에서는 제도 개혁 논의 자체가 실종되기 쉽다.

국내 정치가 진영 결집으로 달아오르는 사이, 대외 지형은 조용히 움직인다. 북미 대화 재개 조짐 속에서 한국의 중재 외교가 트랙 밖으로 밀리는 정황, 평양의 소비 풍경 변화 보도는 대북 접근의 전제가 바뀌고 있음을 시사한다. 여야가 나란히 내치 전선에 몰두하는 만큼, 다음 주 당청 회동에서 정기국회 입법과 함께 대북·외교 기조가 어떤 우선순위로 정리되는지가 지켜볼 대목이다.

### 韓, APEC 보건 협력 이끈다…보건 실무 의장국으로 회의 주재

한국 대표단이 오는 23일부터 26일까지 중국 대련에서 열리는 APEC(아시아태평양경제협력체) 보건실무그룹(HWG) 회의와 ‘건강한 고령화’(스마트 에이징) 워크숍에 의장경제(의장국) 자격으로 참석한다.22일 보건복지부에 따르면 한국은 2026~2027년 보건실무그룹 의장경제로서 지난 2월 중국 광저우에서 열린 제1차 회의부터 올해 작업계획과 향후 5년 보건 협력 로드맵인 ‘HWG 전략계획 2026~2030’ 수립을 주도한 데 이어 개최국인 중국과 함께 이번 회의를 준비해 왔다.APEC에서는 국가

[韓, APEC 보건 협력 이끈다…보건 실무 의장국으로 회의 주재](https://www.donga.com/news/Society/article/all/20260822/134523517/1)

### 🆕 이 대통령, 25일 민주당 지도부 만찬·28일 의원 오찬…당청 소통 강화

이재명 대통령이 다음 주 더불어민주당 신임 지도부와 만찬을 갖고, 28일에는 민주당 의원들을 초청해 오찬을 함께한다. 강유정 청와대 수석대변인이 22일 언론 공지로 일정을 알렸다. 김민석 대표 체제 출범을 계기로 당·청 소통을 강화하는 움직임이다.

**시사점** — 25일 지도부 만찬과 28일 의원 오찬이 김민석 대표 체제 출범 후 당청 관계의 첫 조율 자리다

[이 대통령, 25일 민주당 지도부 만찬·28일 與 의원 오찬…당청 소통 강화](https://www.donga.com/news/Politics/article/all/20260822/134523538/1)

### 이 대통령, 28일 민주당 국회의원 전원 청와대 초청한다

이재명 대통령이 지난 13일 청와대에서 열린 수석보좌관회의에서 발언하고 있다. 청와대사진기자단이재명 대통령이 정기국회를 앞두고 오는 28일 더불어민주당 국회의원 전원을 청와대 영빈관으로 초청해 오찬을 함께한다.강유정 청와대 수석대변인은 22일 언론에 “이 대통령이 오는 28일 민주당 국회의원들을 청와대 영빈관으로 초청해 오찬을 함께할 예정”이라고 밝혔다.민···

[이 대통령, 28일 민주당 국회의원 전원 청와대 초청한다](https://www.khan.co.kr/article/202608221553001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=politic_news)

### [심층분석] 멜로니의 집권, 유럽 ‘강경 우파’ 부상의 경로와 한국 정치의 거울 - 데일리연합

[심층분석] 멜로니의 집권, 유럽 ‘강경 우파’ 부상의 경로와 한국 정치의 거울    데일리연합

[[심층분석] 멜로니의 집권, 유럽 ‘강경 우파’ 부상의 경로와 한국 정치의 거울 - 데일리](https://news.google.com/rss/articles/CBMiW0FVX3lxTE1IX3YySWZCZnB6WDNidkdBZi1CaFBXcExBRzJOTDlPTVVpM09nTHlTbk5UZjd0SjNCcnJVNDhuR213cWtfeUNTR0xGdGY3d2pmaVNNLVZrVUJ5aUE?oc=5)

### 트럼프 다룬 《초권력》을 읽으며 한국 대통령을 논한다 - 피렌체의 식탁

트럼프 다룬 《초권력》을 읽으며 한국 대통령을 논한다    피렌체의 식탁

[트럼프 다룬 《초권력》을 읽으며 한국 대통령을 논한다 - 피렌체의 식탁](https://news.google.com/rss/articles/CBMiakFVX3lxTFBuZ2RpYm1Bd1RuSXBrQXVQbEl3ZE9NWWtiSDdvc0NKa3lhVkY0MUMxU2R5YlNxYkI3ZE5ZcWVWemdnMjFuUWt5b1I5dFZvWlJMNWVaV1N2TnRyYmpwQ0lzSzlXZF8yeXoyeXfSAW5BVV95cUxPaDVGT3c1dEFUY2RPMjRMV01kQkZ6OE9ZNnBvVEpTSVpGYkhVRFd4aEFMME80d0FuWTdRU1JoWmtHSy1uRzhmY3ZwdUZuU0VWYVI3ZV9sQllNcHhqUkhxbWdIaUFma1c3STUxa2RsUQ?oc=5)

### 🆕 김민석 지시 ‘민주당 TV’ 내달 초 출범…‘김어준 방송’ 시간대 겹칠 수도

더불어민주당이 김민석 대표의 지시로 내달 초에 당 자체 TV 채널을 개국한다. 김 대표는 출연 비중이 높을 것으로 알려졌으며, 기존 김어준 방송과 편성 시간이 겹칠 가능성이 있다.

**시사점** — 민주당 TV는 9월 초부터 방송되며, 여당 지지층 확보와 언론 환경 변화에 영향을 미칠 것이므로, 9월 말까지 주요 시청률과 광고주 반응을 주시해야 한다.

[김민석 지시 ‘민주당 TV’ 내달 초 출범…‘김어준 방송’ 시간대 겹칠 수도](https://www.donga.com/news/Politics/article/all/20260822/134523693/1)

### 🆕 “샤넬 화장품 팔고 이케아 매장 등장…예전의 평양 아니다”

외신 보도에 따르면 평양에 샤넬 화장품 매장과 이케아 매장이 들어서면서 고급 소비가 늘고 있다. 2019년 시진핑 주석 방문 당시와 달리 고층 아파트와 명품 매장이 늘어나 북한의 생활양식이 변하고 있다.

**시사점** — 북한의 고가 매장 진입은 남북 관계와 국제 제재 효과를 평가할 때 9월 말까지 북한 내 실물경제 지표와 제재 회피 경로를 주시해야 한다.

[“샤넬 화장품 팔고 이케아 매장 등장…예전의 평양 아니다”](https://www.donga.com/news/Inter/article/all/20260822/134523684/2)

### 국힘 “李, ‘노웅래 무죄’에 숟가락 얹어 검찰 무력화…사법 방탄 멈추라”

국민의힘은 22일 이재명 대통령이 불법 정치자금 수수 혐의로 기소된 뒤 항소심에서 무죄를 선고받은 노웅래 전 더불어민주당 의원에게 공천 배제에 대해 사과한 것과 관련해 “노웅래 무죄에 숟가락 얹어 검찰 무력화 나선 이 대통령은 사법 방탄을 멈추라”라고 했다.박성훈 수석대변인은 이날 논평을 내고 “대통령이 판결의 본질은 외면한 채 기다렸다는 듯 검찰을 악마화하고 특정 정치인의 재판 결과를 검찰 무력화와 사법 방탄의 재료로 삼는 것이 과연 정상적인 국정인가”라며 이같이 말했다.박 수석대변인은 “이번 

[국힘 “李, ‘노웅래 무죄’에 숟가락 얹어 검찰 무력화…사법 방탄 멈추라”](https://www.donga.com/news/Politics/article/all/20260822/134523727/1)

### 김영배, 오세훈 만난 뒤 “용산공원 1㎝도 양보 안 된다며 자기 정치”

더불어민주당 서울시당위원장인 김영배 의원이 22일 주택 공급 등 서울시 현안을 논의하기 위해 오세훈 시장과 회동했으나 이견을 좁히지 못했다. 김 의원은 22일 국회에서 기자들과 만나 “오 시장과 오찬을 하며 격의 없이 주택 공급 정책과 청년 주택 주거의 문제를 포함해 시민을 위해 함께할 수 있는 일에 대해 의견을 교환했다”고 말했다. 그는 “주택 공급과 관련해 함께 검토해야 할 여러 논쟁에 관해 논의가 있었다”며 “결론적으로 큰 합의에 이르는 것은 조금 어려웠다”고 했다. 특히 “용산과 용산 정비

[김영배, 오세훈 만난 뒤 “용산공원 1㎝도 양보 안 된다며 자기 정치”](https://www.donga.com/news/Politics/article/all/20260822/134523712/2)

### 강경숙 조국혁신당 의원, 전북도당위원장 선출

강경숙 조국혁신당 의원. 강 의원 페이스북 갈무리조국혁신당 강경숙 의원(비례)이 전북특별자치도당위원장에 선출됐다.조국혁신당 전북도당은 22일 도당 사무실에서 당원대회를 열고 단독 입후보한 강 의원을 신임 도당위원장으로 선출했다.강 신임 도당위원장은 지난 20일부터 사흘간 진행된 전북지역 당원과 전국 대의원 투표에서 찬성 93.1%를 얻었다. 반대는 6.9%···

[강경숙 조국혁신당 의원, 전북도당위원장 선출](https://www.khan.co.kr/article/202608221724001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=politic_news)

### 장동혁 “李, 노웅래 격려 메시지 낯 뜨거워…자기편은 착한 부패인가”

장동혁 국민의힘 대표는 22일 이재명 대통령이 불법 정치자금 수수 혐의로 기소된 뒤 항소심에서 무죄를 선고받은 노웅래 전 더불어민주당 의원에게 공천 배제에 대해 사과한 것과 관련해 “낯 뜨겁다”고 했다.장 대표는 이날 페이스북에서 “‘돈을 안 받았다’는 판결이 아니다. ‘위법수집증거’가 법원에서 인정받지 못한 것뿐”이라며 이같이 적었다.이어 “그런데도 ‘얼마나 억울했겠냐’며 ‘축하 말씀’까지 전했다. 자기편 부패는 ‘착한 부패’인가”라며 “그러면서 ‘정치권 부패 청산’을 주장한다. 지위와 소속을 막론하고 ‘성역 없이’ 청산하겠다고 한다. 그러려면 본인부터 재판 중지 성역에서 나와야 하는 것 아닌가”라고 했다.그는 “검찰은 해체하면서 정치권 부패를 청산하겠다? 결국 말 잘 듣는 경찰 앞세워 사정 정국으로 몰아

[장동혁 “李, 노웅래 격려 메시지 낯 뜨거워…자기편은 착한 부패인가”](https://www.donga.com/news/Politics/article/all/20260822/134523779/1)

### 김민석, 90도 인사 논란에 “의미도 좋고 보기도 좋은 인사법 다듬어달라”

김민석 더불어민주당 대표와 한병도 원내대표를 비롯한 신임 최고위원들이 20일 국회에서 열린 의원총회에서 고개숙여 인사하고 있다. 박민규 선임기자더불어민주당 김민석 대표가 최근 민주당 의원들이 단체로 ‘90도 인사’를 한 것을 두고 일각에서 ‘과도하다’는 지적이 나온 데 대해 “의미도 좋고 보기도 좋은 단체인사법을 곧 다듬어 주리라 믿는다”고 밝혔다.김 대표···

[김민석, 90도 인사 논란에 “의미도 좋고 보기도 좋은 인사법 다듬어달라”](https://www.khan.co.kr/article/202608222004001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=politic_news)

### [인터뷰] 정세현 "한국 정부, 북한 속사정 파악해 '당근' 챙겨줘야" - v.daum.net

[인터뷰] 정세현 "한국 정부, 북한 속사정 파악해 '당근' 챙겨줘야"    v.daum.net

[[인터뷰] 정세현 "한국 정부, 북한 속사정 파악해 '당근' 챙겨줘야" - v.daum.n](https://news.google.com/rss/articles/CBMiT0FVX3lxTFBPdXZJNkU2aEcyMVZkZlBiX2RTRTVDT0Qwa3dwSU9oSG1DRmNWYXpoUVBicWZ0ZGo4SWo1WWVXVE1PODBSWVZ0YW9lemt5dVk?oc=5)

### 이 대통령, 명진 스님 입적 애도…“불교계 큰 어른 떠나보내”

이재명 대통령이 10일 청와대에서 열린 메가프로젝트 민관합동 제2차 점검회의에서 발언하고 있다. 연합뉴스이재명 대통령이 22일 봉은사 주지를 지낸 명진스님의 입적 소식에 “대한민국 불교계의 큰 어른을 떠나보내게 된 슬픔을 온 국민과 함께 나눈다”며 애도의 뜻을 표했다.이 대통령은 이날 페이스북에 ‘명진 스님의 입적을 애도한다’는 제목의 글을 올려 “갑작스러···

[이 대통령, 명진 스님 입적 애도…“불교계 큰 어른 떠나보내”](https://www.khan.co.kr/article/202608222159001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=politic_news)

### [핫이슈] 구글(Google), 한국 정치 유튜브 449개 무더기 폐쇄⋯보수·진보 ‘생존채널’ 살펴보니⋯ - 일요서울i

[핫이슈] 구글(Google), 한국 정치 유튜브 449개 무더기 폐쇄⋯보수·진보 ‘생존채널’ 살펴보니⋯    일요서울i

[[핫이슈] 구글(Google), 한국 정치 유튜브 449개 무더기 폐쇄⋯보수·진보 ‘생존채](https://news.google.com/rss/articles/CBMib0FVX3lxTE92U2FpSnkyR0FueXBCVFFLeGVaWkExYjZ2WDJRT2dJcjN4TFJIY3RnZ3pQaGpjdDN3TmZkdlJBRTZacGpxd01CdVZYbjNac0JCZjlhMXBTRkJ3akFnSmVHNFJNYnU5TGxzWHQwS1FnZw?oc=5)

### 북미대화 시동에…트랙 밖 밀려나는 페이스메이커 외교 - v.daum.net

북미대화 시동에…트랙 밖 밀려나는 페이스메이커 외교    v.daum.net

[북미대화 시동에…트랙 밖 밀려나는 페이스메이커 외교 - v.daum.net](https://news.google.com/rss/articles/CBMiT0FVX3lxTE9LbDZQM29jYzFGZlVRRHNCRzFoUklFQ2VEOHYwdTBOMDJySnZtbVQxLUlfaVc5RkZpdWplYUc5amhLTmh6UTlvS1lKS0M1SkU?oc=5)

### 산청의 탈북 맏며느리… “산청이 왜 천국인지 아십니까”[북에서 온 이웃]

지난해 봄과 여름, 경남 산청은 기록적인 재난을 두 번이나 겪었다. 3월에 발생한 산불은 축구장 4700개 규모의 면적을 태우고 9일 만에 진화됐다. 4명이 숨지고 10명이 부상을 입었다.화마가 지나간 지 넉 달 뒤, 이번엔 평생 본 적이 없는 수마가 산청을 삼켰다. 단 3일 동안 600㎜가 넘는 비가 쏟아졌고, 닷새로 범위를 넓히면 강우량이 800㎜가 넘었다. 산청에서 기상관측이 시작된 이래 ‘가장 짧은 시간 내에 가장 많은 비’가 내린 것이다.폭우로 곳곳에서 산사태가 발생해 평화롭던 마을들을 

[산청의 탈북 맏며느리… “산청이 왜 천국인지 아십니까”[북에서 온 이웃]](https://www.donga.com/news/Politics/article/all/20260820/134512613/1)

### ‘공무원 폭행’ 인천 계양구의원 출석정지 30일 징계···정의당 ‘솜방망이’ 반발

지난달 8일 인천 계양구의회 개원식이 열리고 있다. 계양구의회 제공워크숍에서 공무원을 폭행한 인천 계양구의원에 대해 출석정지 30일 징계가 내려졌다. 정의당은 ‘솜방망이’ 징계라며 강력 규탄했다.인천 계양구의회는 지난 21일 본회의를 열고 여 의원(42)에 대한 징계안을 심사한 뒤 30일 출석 정지를 의결했다고 23일 밝혔다. 당초 의회 윤리특별위원회는 여···

[‘공무원 폭행’ 인천 계양구의원 출석정지 30일 징계···정의당 ‘솜방망이’ 반발](https://www.khan.co.kr/article/202608231040001/?utm_source=khan_rss&utm_medium=rss&utm_campaign=politic_news)

### 🆕 정부 부동산 세제 개편안, 비거주 1주택자 종부세 놓고 당정 보완 논의

정부가 비거주 1주택자의 보유세와 양도세를 동시에 강화하는 부동산 세제 개편안을 내놨다. 더불어민주당 김민석 대표는 23일 비거주 사유를 폭넓게 인정해 사각지대를 없애야 한다며 보완을 요구했다. 한성숙 국무총리도 같은 날 고위당정협의회에서 세제 개편을 신속하고 정교하게 다루겠다고 밝혔다.

**시사점** — 27일 시작되는 정기국회 세법 심사에서 비거주 1주택자 보유세·양도세 강화 범위가 최대 쟁점이다

[김민석 “비거주 1주택자 종부세 등 세제 개편 숙의 필요”](https://www.donga.com/news/Politics/article/all/20260823/134524625/2)

### 🆕 국민의힘, 27일 의원 연찬회에 박근혜 전 대통령 공식 초청

국민의힘이 27일부터 열리는 정기국회 대비 의원 연찬회에 박근혜 전 대통령을 공식 초청했다. 더불어민주당은 이를 국정농단·부정부패의 시대로 돌아가는 것이라고 비판했다. 이주희 원내대변인이 23일 서면브리핑에서 이같이 밝혔다.

**시사점** — 27일 연찬회에 박근혜 전 대통령 참석 여부가 보수 결집과 여야 대치의 시험대다

[與 “연찬회에 박근혜 초청한 국힘, 국정농단 시대로 돌아가겠단 것인가”](https://www.donga.com/news/Politics/article/all/20260823/134524591/1)

## 세계

**오늘의 분석**

오늘 세계 뉴스를 관통하는 축은 '경제가 곧 전선'이라는 인식이다. 미국은 캐나다산 제품에 50% 관세를 발효했고 협상은 결렬됐으며, 카니 총리는 '미국과 전쟁 중'이라는 표현까지 꺼냈다. 그러나 같은 날 트럼프 행정부가 물가 압박을 이유로 다진 소고기 관세를 면제한 대목은, 관세 공세가 결국 자국 소비자와 채권 시장으로 되돌아온다는 신호다. 국채 금리가 급등하자 재무장관이 재매입 확대로 진화에 나선 장면이 그 청구서에 해당한다. 힘으로 밀어붙인 관세일수록 반작용의 관리 비용이 커진다는 점이 드러난 하루다.

전쟁터에서도 표적이 경제로 옮겨가고 있다. 우크라이나 드론이 러시아 2위 온라인몰 물류센터를 멈춰 세우자 푸틴은 '판도라 상자'를 열었다며 파괴적 보복을 경고했고, 러시아는 쇼핑몰에 '더블 탭' 드론 공격으로 최소 16명을 숨지게 했다. 이 소모전의 뒤편에 북한이 있다. 8500명 파병과 KN-30을 포함한 미사일 50발 이전은 북한이 러시아 전쟁 경제에 실질적으로 편입됐음을 보여준다. 반면 워싱턴에서 북미회담은 여전히 정쟁의 상징적 소재에 머문다. 군사적 밀착은 깊어지는데 외교는 말잔치에 그친다는 비대칭이 선명하다.

동아시아에서는 일본의 사상 첫 130조엔 예산 요구와 4년 연속 최대 방위비가 북한의 '침략전쟁 준비' 규탄을 불렀고, 중국·인도네시아의 밀착과 대만해협 긴장이 여기에 겹친다. 무역·전쟁·군비 증강은 저마다 다른 무대처럼 보이지만, 규칙보다 힘으로 상대를 압박하는 같은 문법을 공유한다. 앞으로 주시할 한 가지는 이번 주 엔비디아 실적과 PCE 지표가, 이 힘겨루기 전체의 배경인 세계 경제에 어떤 신호를 던질지다.

### 엘니뇨에 통행 줄인 파나마운하…美 '안방 경제' 직격탄 - 연합뉴스

엘니뇨에 통행 줄인 파나마운하…美 '안방 경제' 직격탄    연합뉴스    엘니뇨發 가뭄 중남미 강타… 파나마 운하까지 말라간다    조선일보    “내년이 올해보다 더 덥다” 기온 상승 불러오는 ‘슈퍼 엘니뇨’ 조짐    v.daum.net    엘니뇨 가뭄에 파나마운하 통항 축소...글로벌 물류 '비상'    YTN    "이런 신호 처음"…역대 최강 엘니뇨, 2027년 '가장 더운 해' 온다    뉴시스

[엘니뇨에 통행 줄인 파나마운하…美 '안방 경제' 직격탄 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE5GMjFzX0xkQnFTWmJlSzl3ekdWaS1NSjdGeXRyaXdtbHB0a1paTzdOc3VXZ18wVFVRZjc5M05ROVRWWk5YNU9BaGRuNnRaMXhUck1PVGhYVU5DUEXSAWBBVV95cUxPa0hDVFhEdU9KalU4UUtFdWJIUDEwNUxoOG1YUWRYdmpMby1SRWZNaWx1NHRXSkJ4UVZoZVNvOFJLQWUtRU83cmt6OG9MVGFLZ2EyX0s3YXFpX2NlbFg1NmI?oc=5)

### 미 민주, ‘북미회담’ 공세 강화…“김정은에 굴복” - KBS 뉴스

미 민주, ‘북미회담’ 공세 강화…“김정은에 굴복”    KBS 뉴스   Google 뉴스에서 헤드라인 및 의견 더보기

[미 민주, ‘북미회담’ 공세 강화…“김정은에 굴복” - KBS 뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE1Ud3pmMGJGU1kzSGZ5NndUcTFZRWtsd3h2bzd6aldWTnRxZjhkRFVsai1lTzdHQ0RMandRREdZZ2o0WTJncld4cnlNTnljNGxWMjdZNzFOaDV2T2M?oc=5)

### 우크라 정보국 '러 파병 북한군 현재 8,500명…드론부대 포함'

우크라이나 정보국은 러시아에 파병된 북한군이 현재 8,500명이라고 밝혔다. 여기에는 정찰·공격용 드론부대도 포함됐다고 설명했다.

**시사점** — 파병 규모가 8,500명으로 커지고 드론부대까지 편성된 만큼, 러시아에서 쌓은 실전 경험이 한반도로 환류될 위험을 주시해야 한다

[우크라이나 정보국 "러 파병 북한군 현재 8,500명‥드론부대 포함" - MBC 뉴스](https://news.google.com/rss/articles/CBMidEFVX3lxTE9tbVZEdVpMMDlxWTRjbjYwWmJqTDY0MDdCSEVyQ013UXNVRmt0Y2RRNFRxaEJBS3FGRTFtR1NBYnBkaXdOSTJYUE1Yc1hLLUxTMEZiaElnNWV3N3k3dnVaTEpOU0hzM0c5ZkJLNjRYbEVUTjlw0gF0QVVfeXFMTkpqWG1LcHhhSVR6Vk5yaDd2MjRUODNQUGgtRGg5d0J3aF9tUGJ6cVhhSUdCdTlLay00RzR6c2NjampPR1pyZGFDZ1dWRS1mbV9jSWxPakFORHc5MF9peldWMm1sbEFQOXBvZFlqLXVxTFViekw?oc=5)

### 🆕 캐나다, 美 50% 관세에 '달러 대 달러' 맞대응…무역협상 결렬

미국이 200억 달러 규모 캐나다산 수입품에 50% 관세를 발효했다. 막판 무역협상이 결렬된 직후다. 캐나다는 같은 규모로 보복 관세를 부과하겠다고 밝혔다.

**시사점** — 미·캐나다 관세전이 전면화하는 국면인 만큼, 대미 수출 협상을 앞둔 한국은 200억 달러 규모 후속 보복 품목 목록을 주시해야 한다

[Canada says it will match US tariffs 'dollar for d](https://www.bbc.co.uk/news/articles/cvgvyy4x2mvo?at_medium=RSS&at_campaign=rss)

### 🆕 北 '日 역대 최대 방위비 편성은 침략전쟁 준비'

북한은 일본이 역대 최대 규모 방위비 편성을 추진하는 데 대해 '침략전쟁 준비'라고 주장했다. 일본은 방위산업 부문을 통합·재편하는 기업에 정부가 직접 출자하는 방안도 추진한다.

**시사점** — 일본 정부의 방산기업 직접 출자는 동북아 무기 수출 시장에서 한국 방산업체의 경쟁 상대를 키우는 변수다

[北, 日역대 최대규모 방위비 편성 추진에 "침략전쟁 준비" 주장 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE9fSEtjbDVDb093OFdpMFRqYUp0eTl1U2kzQ3Y5RVRqSTc1alMzVGhLRm5EWkpWeDBOUDU5SjRUSlZsT040OGg1QUpGTE4xUVBQMDFmU3JsOTFsSmfSAWBBVV95cUxPdzNGVE5PTEhObnVvdEJRdE1uclVmWjBLZGU4ZU9Tb1ctQXl6SFJ2TVFGbFo3ZEZUbXRkXzY3dGhqc01sRFFXUnBfMmd4emdqY3hiZWtqQ1E5cjFRSjB0b0g?oc=5)

### 🆕 美 연방법원, 트럼프 '75개국 비자 중단' 무효…백악관 침묵

미국 연방법원이 트럼프 행정부의 75개국 이민 비자 중단 조치에 제동을 걸어 무효로 판단했다. 백악관은 별다른 입장을 내지 않았다.

**시사점** — 행정부가 항소하면 판결이 뒤집힐 수 있어, 미국 이민·취업비자를 준비하는 이들은 대상 75개국 명단과 항소 결과를 주시해야 한다

[미 연방법원, ‘75개국 이민 비자 중단’ 제동…백악관 침묵 - 한겨레](https://news.google.com/rss/articles/CBMib0FVX3lxTE9NX0tocVpOMDF1dFdCXzdKaEhXc2ZqZHREOU9hV05zSHByZnZDOGh4ZXotclN5cTU0TzhEVDV3MnY0Smhvd2Y2enVPX0dGdHZHM2lxUUdYckxRcml1LTJUZ3htVUtmeHFNM1RPN0hiUQ?oc=5)

### 🆕 트럼프, 다진 소고기 관세 면제…美 목장주 '배신' 반발

트럼프 대통령이 다진 소고기에 대한 관세를 면제하기로 했다. 물가 압박을 낮추려는 조치다. 미국 목장주와 축산단체는 '배신'이라며 반발했다.

**시사점** — 트럼프가 물가를 잡으려 관세를 푸는 국면인 만큼, 연준 금리 결정을 앞두고 미국 인플레이션 지표가 원/달러 환율의 변수다

[트럼프, 다진 소고기 관세 면제…“사회주의보다 나빠” 美축협 반발 - 동아일보](https://news.google.com/rss/articles/CBMic0FVX3lxTFB3ZEltV1BYMFVWZWJwRnE1MlpEaE9tdUlqTVBFYnlhSEt4SjRfTXZDOVlBVFVWMlRGbGNqeENSZkEtNV8xUk1kN2x6YzRPbUtFelNibVlqbkN2aXZjN2RtYXRWTkFseGNMdlRnZ3BpX3hfaDTSAWZBVV95cUxNejVGMUg2cG90ZEhLaWFTM1NlM2cybnkxMEJtamhfLTNPRUROYVNpOVZ1eFB5U2JtSFJ1VE1fMlhDandPTnM2aDcwb2RnSkxHMDRtQ0JMbk5RMjNxNEpBTE5Xa294OHc?oc=5)

### 미·캐나다 무역협상 결렬…트럼프 50% 관세 발효 - 노컷뉴스

미·캐나다 무역협상 결렬…트럼프 50% 관세 발효    노컷뉴스    미국-캐나다, 무역협상 결렬…美, 캐나다산 제품에 50% 관세 부과    동아일보    미·캐나다 무역협상 결렬…트럼프 신규 관세 현실화    KBS 뉴스    캐나다산 철강 25%·車 15%로 관세인하 논의…美와 막판 조율    연합뉴스    美·캐나다 무역협상 막판 결렬, 50% 관세 발효… 캐나다 "같은 규모로 보복"    조선일보

[미·캐나다 무역협상 결렬…트럼프 50% 관세 발효 - 노컷뉴스](https://news.google.com/rss/articles/CBMiUkFVX3lxTE02c0NqVkp1Ui0xUUJ6Q3YtUzVvWlplOXprQU1xY0hGY0dpWGNPMXYzUUZ0WV92WTNhUDlVemhPenRCYjI2WU5IOVNJMnF3SDNzQUE?oc=5)

### ‘트럼프 女참모’ 논란 의식? 멜라니아 “나 그리웠지?” - 동아일보

‘트럼프 女참모’ 논란 의식? 멜라니아 “나 그리웠지?”    동아일보    ‘트럼프 불륜 의혹’에 여사 등판…“저 보고 싶었죠?” [지금뉴스]    v.daum.net    에어포스원 탑승하는 나탈리 하프 보좌관    뉴시스    트럼프 애착 담요?...백악관 꽉 잡은 문고리 3인방    서울경제    [W 언박싱] “저 보고 싶었죠?”…‘트럼프 불륜 의혹’에 여사 등판    KBS 뉴스

[‘트럼프 女참모’ 논란 의식? 멜라니아 “나 그리웠지?” - 동아일보](https://news.google.com/rss/articles/CBMic0FVX3lxTE0zV1EwZzJCZmhiRTh5emNLdnAzUFo3LWdvazIyM25jRndzUVJVR01RTlpXbUo4NnI3TzA0NjdwbXZRN3JUUkRrVEc2UWVzQXk3TjNBSk5rQnJSVmpyTmNTUVo4ZHI3NWtRSDd6SjF6RVZjc1HSAWZBVV95cUxNa3lKc0xJd2VsVk53LXBrV3FHUkRqTmpVSHNGTDVCcmRQejRvZjBTSkxYXzUtd2RPRXRlem1QU1ljeVE0c2UwVlotNnctWGFYdU90d3JzSDl3SnU2cE1OMXdsYzNjVHc?oc=5)

### 🆕 중동·이슬람 8개국 '이스라엘, 서안 정착촌 확대 중단하라'

중동·이슬람 8개국이 이스라엘의 요르단강 서안 정착촌 확대를 규탄하며 중단을 촉구했다. 이스라엘은 국제사회 비판에도 서안 정착촌 건설을 계속 추진하고 있다.

**시사점** — 8개국이 공동 규탄한 만큼 이스라엘의 실제 서안 정착촌 착공 여부와 미국의 입장 변화를 주시해야 한다.

[중동·이슬람 8개국 "이스라엘 서안 정착촌 확대 중단하라" - YTN](https://news.google.com/rss/articles/CBMiXkFVX3lxTE5XV1ZtaGszcHlRRUk2RXNlbUF1b1FyYnVNbkRDWDJZQnB0NmpOS1hMRlhKTUxOVzFLb1Y2ZVZUeEFJdEFuUEEyZWhlMFBZRjc4eG5UeDloNEFOdkRNdkE?oc=5)

### 🆕 포로 된 우크라 태생 군인들, BBC에 '러시아 편에서 싸운 이유' 밝혀

포로로 붙잡힌 우크라이나 태생 군인들이 러시아 편에서 싸운 이유를 BBC에 밝혔다. 러시아와 우크라이나는 전쟁 포로 206명을 교환했다.

**시사점** — 러·우가 포로 206명을 교환한 만큼 추가 포로 교환 협상이 재개될지가 다음 관전 포인트다.

[우크라이나 전쟁: 포로로 붙잡힌 우크라 태생 군인들이 BBC에 밝힌 '러시아 편에 선 이유](https://news.google.com/rss/articles/CBMiXEFVX3lxTE1CNjR6bnVEbFVRdndDSGlkam1ZUlU1cjNodnVZMFBtYTVXSWctUF9hcDBHRXRSUVloaDNJdmdoNHlJSzllaVBVTkNlZ21URV9samxCcGlQb3I5azBn0gFiQVVfeXFMTmZZc0d5TEtIZHhacDl4NjlhRF9MZGVnNFpNWU80eUR4OVQ0M3pncC0xOENMWlBzNGxVbHZwOHJ1b3hfQ0I5N21RckYzUEdxZTdTMU43azBMaHJjSXNSQTVSalE?oc=5)

### 🆕 세우타 이주 참사 3주 만에 장례…사망자 95% 신원 미상

스페인 역외 영토 세우타의 이주민 참사 3주 만에 희생자 장례가 치러졌다. 사망자의 95%는 아직 신원이 확인되지 않았다.

**시사점** — 사망자 95%의 신원이 확인되지 않아 세우타 이주 참사의 책임 규명이 장기화할 전망이다.

[세우타 사태 3주 만에 장례… 사망자 95% 신원도 모른다 - 조선일보](https://news.google.com/rss/articles/CBMiigFBVV95cUxNTW9TR1RwRGhmWU5jZFpOQWp5NXdUNmtVeTdmS3l0dUFiTDdObzJyM25Ib1d4SFoxOWRsZmtVUTJpU2ZyYVA2cWFkSG9ZN19MQ1NSNjRKMzVWLWlrT0UtTG9WRDJWQ211ZlZLNWtGeE16M2Z4RDdPTkxSdDJvTklBRDA4ZHNLbm5iTVE?oc=5)

### 🆕 일본 사상 첫 130조엔 방위비 추진에 북한 “철저히 반격”

일본 정부 각 부처의 2027회계연도 예산 요구액이 사상 최대인 130조엔을 넘어설 전망이며, AI·반도체·방위비 확대가 골자다. 북한은 이를 침략전쟁 준비로 규정하고 철저히 반격하겠다고 반발했다.

**시사점** — 130조엔 예산 요구안이 일본 국회를 통과하는지, 증액된 방위비가 한반도 겨냥 무장에 얼마나 배정되는지가 관건이다.

[북한, 일본 최대 방위비 편성 추진에 “침략전쟁 준비…철저히 반격할 것” - 한겨레](https://news.google.com/rss/articles/CBMiaEFVX3lxTE0yZE1leHh3Z194MHoxcEVWZmpTUFp2emx6azJTalM3R0E4am1JTGhBNTR6QzY1dmgyNTF0TXBlcHpzNnk1ODc2SFByV3d5XzRNSVA3cVRDaE5hNnlLTDVBMnZpYVJyMFUw?oc=5)

### 🆕 中·인니 ‘2+2 대화’로 밀착…같은 날 美초계기 대만해협 통과

대만 동부 해상에서 합동훈련을 한 중국과 인도네시아가 21일 외교·국방 장관 ‘2+2 대화’로 밀착을 과시했다. 같은 날 미국 초계기가 대만해협을 통과하며 미중 긴장이 다시 부각됐다.

**시사점** — 대만해협 긴장이 고조되면 한국의 에너지 수입선과 통상 항로가 직접 위험에 노출되므로 초계기 통과 빈도를 주시해야 한다.

[中·인니 '2+2 대화'로 밀착한 날…美초계기는 대만해협 통과(종합)](https://www.yna.co.kr/view/AKR20260822027751089)

### 🆕 앤트로픽, 기업가치 2조 달러 IPO 추진…성공 시 역대 최대

AI 기업 앤트로픽이 기업가치 2조 달러(약 2천780조 원)를 목표로 기업공개(IPO)를 추진한다. 성공하면 역대 최대 규모의 상장이 된다.

**시사점** — 앤트로픽이 2조 달러 밸류로 상장하면 국내 AI·반도체 기업의 대미 투자와 기업가치 재산정 기준이 바뀐다.

[앤트로픽, '기업가치 2조 달러' IPO 추진…성공시 역대 최대](https://www.yna.co.kr/view/AKR20260822032000009)

### 러 폭격에 이틀째 우크라 민간 사상자 속출…사망 70%↑

러시아의 계속된 공격으로 우크라이나 도심에서 이틀째 민간인 사상자가 속출했다. 민간인 사망자는 전보다 70% 이상 늘었다.

**시사점** — 민간인 사망이 70% 늘며 종전 논의가 공전하는 만큼, 우크라 재건을 노리는 국내 건설·방산 기업의 진출 시점이 밀린다.

[러 폭격에 이틀째 우크라 사상자 속출…민간인 사망 70%↑](https://www.yna.co.kr/view/AKR20260822038000109)

### 🆕 美 연방법원, 75개국 이민비자 중단 조치에 제동

미국 연방법원이 75개국을 대상으로 이민비자 발급을 중단한 트럼프 행정부의 조치에 제동을 걸었다.

**시사점** — 트럼프 행정부가 항소하면 75개국 출신 이민비자 신청자의 발급 재개 시점이 다시 불투명해진다.

[美 연방법원, 75개국 대상 이민 비자 중단 조치에 제동](https://www.yna.co.kr/view/AKR20260822027400009)

### 🆕 미얀마군, 불교사찰 폭격…하안거 수련 14명 사망

미얀마 군정이 민간인을 상대로 공격을 늘리는 가운데 불교사찰을 폭격했다. 하안거 참선수련을 하던 14명이 숨졌다.

**시사점** — 하안거 수련 중 14명이 숨지며, 아세안(ASEAN) 회의에서 미얀마 군정 배제 논의가 다시 불거질 수 있다.

[미얀마군, 불교사찰 폭격…하안거 참선수련하던 14명 사망](https://www.yna.co.kr/view/AKR20260822028800084)

### 🆕 삼성·SK 위협하는 中 낸드 YMTC, IPO로 6조8천억원 조달 추진

중국 낸드플래시 업체 YMTC가 기업공개(IPO)로 6조8천억원을 조달할 계획이다. YMTC는 삼성전자와 SK하이닉스에 도전하는 중국 메모리 업체다. D램 분야 창신커지(CXMT)에 이어 낸드 분야에서 상장을 추진한다.

**시사점** — 삼성전자·SK하이닉스는 YMTC의 6조8천억원 조달 이후 낸드 증설 속도와 가격 하락 압박을 주시해야 한다.

['삼전닉스에 도전' 中낸드 YMTC, IPO로 6조8천억원 조달 계획(종합)](https://www.yna.co.kr/view/AKR20260822023851089)

### 🆕 우크라 방산업체 CEO “사거리 300㎞ 탄도미사일 9월 말 전력화”

우크라이나 방산업체 파이어포인트의 CEO가 사거리 300㎞ 탄도미사일을 9월 말 전력화하겠다고 밝혔다. 우크라이나는 자체 탄도미사일로 러시아를 공격할 역량 확보를 추진하고 있다.

**시사점** — 9월 말 300㎞ 탄도미사일 전력화 시점이 러시아 후방 타격 범위와 종전 협상 판도의 변수다.

[우크라 방산업체 '파이어포인트' CEO "사거리 300㎞ 탄도미사일 9월 말 전력화" - ](https://news.google.com/rss/articles/CBMiXEFVX3lxTE50Yks3SWZNNnpVa1VCUEY4Ymw4MXJXd0RxY3VuNUt2TGhvdEx5dkpzY3B4RnltZVFfQ0diQ09GMGdRcXlhM3l3WW1rOGZEdXJ0QkR6OUQ0dl80a1Et?oc=5)

### 🆕 팔레스타인 10대, 이스라엘 정착민 총격에 숨져…8개국 정착촌 확대 규탄

이스라엘 정착민의 총격으로 팔레스타인 10대가 숨졌다. 중동·이슬람 8개국이 이스라엘의 서안 정착촌 확대를 규탄했다.

**시사점** — 8개국의 규탄이 실제 대응으로 이어질지, 서안 정착촌 확대 속도가 다음 분기 중동 정세를 가른다.

[팔레스타인 10대, 이스라엘 정착민 총에 숨져..."정착촌 확대 멈춰라" 비판 - YTN](https://news.google.com/rss/articles/CBMiXkFVX3lxTFBpc05iQUZ2VnBUUkZabHhaX0x0LU92RnZMYVJzZVpYU1pvWlpQTm83THl5bXczLS1IYnhSYkF6OGxncGRBai1venZvM2VXUFJ0c0M4TUw2TFgwNFRqZVE?oc=5)

### 🆕 소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째

예멘 앞바다에서 유조선 한 척이 소말리아 해적에 납치됐다고 AP통신이 보도했다. 4월 이후 6번째 납치다.

**시사점** — 4월 이후 6번째 납치로, 예멘 인근 항로를 지나는 한국 해운사의 보험료와 우회 비용이 오를 수 있다.

["소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째"](https://www.yna.co.kr/view/AKR20260822040200109)

### 🆕 미얀마군, 불교 사찰 폭격…참선 수련 14명 사망 추정

미얀마군이 불교 사찰을 폭격해 14명이 사망하고 20명이 다친 것으로 추정된다. 사망자들은 하안거 기간에 참선 수련을 하던 중이었다.

**시사점** — 불교 국가에서 군이 종교시설을 친 사건으로, 아세안의 미얀마 군정 규탄 수위와 추가 제재 논의가 관건이다

[미얀마군, 불교 사찰 폭격…14명 사망·20명 부상 추정 - 노컷뉴스](https://news.google.com/rss/articles/CBMiUkFVX3lxTFBrNWNrdXhNcmJCWXVhTUdkTnpCVi1VcmV3SkZpTzhyMmxnZ3V1WXFpMGpHUllHczFHWVZzMVRBZUp1NFVvVGNqVDdVQ1FTc1FuSnc?oc=5)

### 소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째

소말리아 해적이 예멘 앞바다에서 유조선을 납치했다. 4월 이후 여섯 번째 사건으로, 이란을 둘러싼 전쟁이 해적에게 기회가 됐다는 분석이 나온다.

**시사점** — 홍해·아덴만을 지나는 유조선 보험료와 국제유가가 추가로 오를지가 국내 해운·정유업계의 관건이다

["소말리아 해적, 예멘 앞바다서 유조선 납치‥4월 이후 6번째" - MBC 뉴스](https://news.google.com/rss/articles/CBMidEFVX3lxTE0zbW1NUjJmWjhMSTY3REhEUVBSZmdoaE9IcUJaSDU2UmxCZDE5dldBQkIteUpMZVlvaTRUVTU5ZlZ3S3FHTXg0R0ZNRDljMXRBTHhWS3NMUlJZRzhqWUd3QWVRUlZRNk9tNy1ldWxLR3pWWVJu0gF0QVVfeXFMUFN4cTFFSXN6cDNEY1ppY2NDMlJVZkpFRDVRQWJRVXgyQUlDajlZdlp4dTJzNlhHT0tfTzQ5RHVTb1N0dTJZWDd3UFJCRVZJWEFFWXdQcjFXVWlZbTlkWUZhb1dMZlZJdkJjb3phelVnZS1aZUE?oc=5)

### 🆕 EU 규정에도 난민 이송 거부…이탈리아로 재이송

난민이 처음 입국한 국가가 망명 심사를 책임지도록 한 EU 규정에도 일부 회원국이 이송을 거부했다. 이탈리아로 입국한 신청자는 다시 이탈리아로 돌려보내졌다.

**시사점** — 이탈리아 등 남유럽 관문국과 여타 EU 회원국 간 난민 분담 갈등이 재점화될지 주목된다

[이탈리아로 입국한 유럽 난민 신청자, 다시 이탈리아로](https://www.yna.co.kr/view/AKR20260822042600109)

### 🆕 이란 협상파 최고위 정치인들 "전쟁 끝내고 경제 회복"…강경파와 공개 대립

이란의 협상파 최고위 정치인들이 미국과의 전쟁을 끝내고 경제를 회복해야 한다고 주장했다. 이들은 내부 강경파를 향해 사실상 공개적으로 대립각을 세웠다.

**시사점** — 협상파가 우위를 잡는지 여부가 대이란 제재 완화와 국제유가 향방을 가르는 변수다

[이란 협상파 "전쟁 끝내고 경제 회복할 때"…강경파에 대립각](https://www.yna.co.kr/view/AKR20260822045400009)

### 🆕 소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째

소말리아 해적이 예멘 앞바다에서 유조선 한 척을 납치했다. 이는 지난 4월 이후 여섯 번째 피랍이다.

**시사점** — 4월 이후 6번째 피랍으로 예멘 앞바다 항로의 유조선 운임과 보험료가 다시 오를 변수다

["소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째" - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE9qN0F1Zl9USFhuV1NrbGJFVkhQNmtpU2EtcWpuZGFHWF9vR3p6dXhxa3V3dUprR3FJb09qcXNDbU40b1A5Tm4xcXdDZTB1S1NLZWFsVkpQeVdrYk3SAWBBVV95cUxNX3BrTUZ2eE91OVJYWndBb1FscTZyWUNvSmZhaHdELVJ2TXlXWWpZODI4TVBFaDVKZGNmUEs5MTYzUTZDNW1TMHZEbnRxZGpPdzZSdmFYRkd2YjR5MHRWRU8?oc=5)

### 🆕 베이징서 휴머노이드 로봇 운동회 개막…달리기부터 가사 서비스까지 겨뤄

베이징에서 휴머노이드 로봇 운동회가 개막했다. 로봇들은 달리기와 공차기 등 운동 경기는 물론 조립과 가사 서비스 능력까지 겨룬다.

**시사점** — 가사·조립 종목 성적이 중국 휴머노이드의 실사용 수준을 가늠할 지표다

["축구부터 콩 집기·병뚜껑 열기까지"…베이징서 로봇운동회 개막](https://www.yna.co.kr/view/AKR20260822045900083)

### 우크라 “러 파병 북한군 8500명…드론부대 포함”

우크라이나는 러시아에 배치된 북한군이 현재 8500명이며 드론부대가 포함됐다고 주장했다. 9월 푸틴·김정은 회동에서 최대 5만명 규모의 추가 파병 가능성도 제기됐다.

**시사점** — 9월 푸틴·김정은 회동에서 5만명 규모 추가 파병이 결정될지가 관건이다

["러 파병 북한군 현재 8,500명…드론부대 포함" - 연합뉴스TV](https://news.google.com/rss/articles/CBMiZ0FVX3lxTE44RUNfdnZRWFB3YVNjTWliWG41a05qdlRkTzBETnhhZ3dRUVktVXhEWTlZdjlKNW1ST3NLVTlRQUpoY3h5V3lqc2xQTjV2RkJoNHE4bmlQLU5vWmZSeE1BS2haWkJrV0E?oc=5)

### 🆕 일본 예산 요구 첫 130조엔 돌파 전망…방위비 4년 연속 최대

일본 정부의 내년도 예산 요구액이 사상 처음 130조엔을 넘어설 전망이며, 방위비는 4년 연속 역대 최대 규모다. 일본 정부는 방산기업의 주주로도 참여한다. 북한은 이를 '침략전쟁 준비'라고 비난했다.

**시사점** — 일본이 방산기업 주주로 나서며 130조엔·역대 방위비를 추진하는 만큼, 확정 예산 규모와 북한의 '침략전쟁' 반발이 동북아 군비 경쟁의 가늠자다.

[日정부 예산요구 사상 첫 130조엔 돌파 전망…4년연속 최대 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE9qZ2REVEQ2ZVRFTjd6UjZRSllCdTVvM0pDcjRQYm44UFVtQkdhdFVJck5WazFHVEs1czNISF9wMkFNcFRvSFNpYlczWWZKMmNwQkNXOXJNUWhKSUXSAWBBVV95cUxQZWdRaElfM1QyNFNQLVlUN0FYd3lWOS1Pck4xQWQtcjV6WDQwamRxdzBSbzdHLTdNUDZZcF95Q3Mwd1R6eVhaWTVWVnFHUU44SEVvQ1dnbGcydWVDVHI0NjQ?oc=5)

### 이란, 이라크 유조선 호르무즈 해협 통과 특별 허용

이란이 이라크 일부 유조선의 호르무즈 해협 통과를 특별 허용했다. 이란은 호르무즈 동쪽 해역에 대한 통제를 주장하며 긴장이 이어지고 있다.

**시사점** — 한국 원유 수입의 상당분이 호르무즈를 지나는 만큼, 이란의 동쪽 해역 통제 주장과 선별적 통과 허용은 유가·전쟁보험료를 흔들 변수다.

[이란, 이라크 유조선에 호르무즈 해협 통과 허용 - 경향신문](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9RRFFZaVg5N1hoX0NaNnRRZmE5Ul9haVJHMmVSUy1XQ0R5WWExazZ1S2FnMjVSa004UjNxNjJLc3BOQkx3cVNmV1pETWlTOHVfUC00V3NQZDh3Z9IBX0FVX3lxTFBBVDQ5WWVRSERBQXVTWlNiUWNDVFBueHBYalJhU1hkdURGazdJWmZDdDlpSzJtNHFfNkdfVl9WbEZhQ2FNckQxR01JTXVkQlZzckZySGZIZl9TSnhNSVJn?oc=5)

### 🆕 중동·이슬람권 8개국, 이스라엘 서안 정착촌 확대 중단 촉구

중동·이슬람권 8개국이 이스라엘의 서안 정착촌 확대를 규탄하며 중단을 요구했다. 서안에서는 말다툼 끝 총격으로 17살 아들이 숨지는 사건도 발생했다.

**시사점** — 이스라엘이 8개국 규탄을 무시하고 정착촌을 늘리면 서안 유혈 사태가 확산 — 중동 외교·유가 불안의 다음 뇌관이다.

[중동·이슬람권 8개국, 이스라엘의 서안 정착촌 확대 "중단하라" - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE16R0xiM0kydUM2eDZFUkl6Y21VdHNVeVBGeUVFa2kzXzJvQU56Ui1tYl9neURhVTNHZjRXcmxZcHJqYUI0LUFrTHVZc0g0T05FWmhnMjEyZElLRWvSAWBBVV95cUxOX2RKWXVIaDNOeFAwQUNlOHczWHlFQllCaXdPOTFRczRuek9kWTRnazNxdjByV1JNRG9wZmxoMWdhLUxUQnEtdkFTaUlucy14b1NMUkpmUFZVcFloN00xR04?oc=5)

### 🆕 푸틴, 총선 한 달 앞두고 집권당 행사서 결집 호소

우크라이나 전쟁이 장기화하는 가운데 블라디미르 푸틴 러시아 대통령이 22일 집권당 행사에 참석했다. 총선을 한 달 앞두고 지지층 결집을 호소했다.

**시사점** — 전쟁 장기화 속 다음 달 총선은 푸틴 국내 장악력의 시험대로, 결과가 러시아의 우크라이나 협상 태도를 좌우할 변수다.

[우크라전 장기화 속…푸틴, 총선 한달 앞두고 결집 호소](https://www.yna.co.kr/view/AKR20260822047100109)

### 🆕 우크라 정보당국 "러시아, 북한산 탄도미사일 50발 보유…개량형 KN-30 포함"

우크라이나 정보당국은 러시아가 북한산 탄도미사일 약 50발을 보유한 것으로 추정한다고 밝혔다. 여기에는 2.5t 탄두를 갖춘 개량형 KN-30이 포함됐다고 전했다.

**시사점** — 러시아가 우크라이나에 쏘는 북한산 미사일의 개량 여부와 실전 성능이 한국군이 주시할 대응 데이터다

["러, 北미사일 50개 보유 추정…개량형 KN-30 포함" - 연합뉴스TV](https://news.google.com/rss/articles/CBMiZ0FVX3lxTE5WQVM4UUt5Rk1XTXJqbEwxZWlxUVVfMkZtLXdsNjBQUTZXR1BVODk1QzNnQjR0MGxsR3VqUGVwMmdUVEJXazRHVDZOMXlJdTMwZjE1MWo1dEZGV1kwekMzM1dKTTkyWUE?oc=5)

### 🆕 마크롱, '방공망 고갈' 우크라이나에 요격 미사일 지원 약속

에마뉘엘 마크롱 프랑스 대통령은 22일 방공망이 고갈된 우크라이나에 요격 미사일을 지원하겠다고 밝혔다.

**시사점** — 프랑스의 요격 미사일 지원 규모와 인도 시점이 겨울 전 우크라이나 방공 능력의 관건이다

[방공망 바닥난 우크라…마크롱, 요격 미사일 지원 약속](https://www.yna.co.kr/view/AKR20260822049000082)

### 🆕 미얀마 수도원 공격에 14명 사망…명상 수행 중 두 차례 피격

미얀마의 한 수도원 공격으로 14명이 숨졌다. 구조대원은 민간인이 명상 수행을 위해 모인 가운데 현장이 두 차례 타격당했다고 전했다.

[Fourteen killed in strike on Myanmar monastery](https://www.bbc.co.uk/news/articles/cqlxlvz01z1o?at_medium=RSS&at_campaign=rss)

### 🆕 이스라엘, 시리아 남부 공격…1명 부상에 시리아 '주권 침해' 반발

시리아 남부에서 이스라엘의 공격으로 1명이 다쳤다고 AFP통신이 22일 시리아 매체를 인용해 보도했다. 시리아는 이를 주권 침해로 규정했다.

[시리아 남부서 이스라엘 공격에 1명 부상…시리아 "주권 침해"](https://www.yna.co.kr/view/AKR20260822049500109)

### 🆕 러시아, 북한 미사일 50발 비축…'2.5t 탄두' KN-30까지 확보

러시아가 북한산 미사일 50발을 비축한 것으로 파악됐다. 여기에는 2.5t급 탄두를 탑재하는 KN-30도 포함된 것으로 전해졌다.

**시사점** — 북한이 대가로 받을 러시아 기술과 KN-30의 실전 축적 데이터를 주시해야 한다

[北 미사일 50발 쌓아둔 러시아…'2.5t 탄두' KN-30도 넘겼다 - 파이낸셜뉴스](https://news.google.com/rss/articles/CBMiWkFVX3lxTE1Qdi03TFh5bEJQLWxQVExqem11UklLZHUzSEtyQTZZOV9ka1RpbHJlTF9iZHp0WlJTUWxwTkpTZmdFRF9Oazg3UkMxb090YzVTZncwWEFKNWdsUQ?oc=5)

### 캐나다, 트럼프 새 관세에 '오판'…무역협상 결렬

마크 카니 캐나다 총리가 22일(현지시간) 연설에서 트럼프 대통령의 새 관세를 '오판'이라고 비판했다. 카니 총리는 주권을 지키기 위해 캐나다가 협상 테이블에서 물러났다고 밝혔다.

**시사점** — 무역협상이 결렬돼 관세 분쟁이 장기화되면, 북미 생산망에 묶인 한국 수출기업은 협상 재개 시점을 주시해야 한다.

[Carney calls Trump's fresh tariffs a 'miscalculati](https://www.bbc.co.uk/news/articles/cx272np7vgyo?at_medium=RSS&at_campaign=rss)

### 🆕 우크라 드론, 러시아 2위 온라인몰 물류센터 타격…운영 중단

우크라이나 드론 공격으로 러시아 2위 온라인몰의 물류센터가 타격을 입고 운영이 중단됐다. 러시아의 폭격으로 우크라이나에서도 이틀째 사상자가 이어지며 민간인 사망이 70% 이상 늘었다.

**시사점** — 우크라이나가 러시아 소비·물류 인프라로 표적을 넓히면서, 전쟁 장기화와 러시아 내수 타격 정도가 관전 포인트다.

[우크라 드론 공격에 러시아 2위 온라인몰 물류센터 타격… 운영 중단 - 조선비즈 - Cho](https://news.google.com/rss/articles/CBMingFBVV95cUxNdnZPWHpEdzdYU2g1VVh2dDBaTWI3U0o3czM1WmdBMUdhdnVwVEJ6M3ZUeDNlamFwVENnZklNeFhLRmF2RGZsalRQWUY0LTFkRUNkWXZkTUhwNWZTN2dhdnpJZUttbl8xakpGRWU1UEdTa21lVHpwOXBCUU9kTjk2QnVOTW9XR19lWXl4cFc5ZEZXa1h3TGxRZ1ppQ3VCd9IBsgFBVV95cUxQVVFUMzNwYVBvb3FhaEhjNEwzYV9nOS1LYWpKNGFZby1XbHE2QzNSNzlYMzdGQ2p3ZnFlTUdnRE1HaTUwRG9UYUVBS0lkdWVQM1NVb2xCaHJXRjFpTmtZWmVyT2NRa0laZUhxWHFzWkItVFdLZ0xnWnJiVWQ1MUoxMS1pXzRWRE1fdkFjd0YyNkVoYUltQkhOaWJBa0VjLWtreDVPR0R4a0NhX0xmcHVZenln?oc=5)

### 🆕 스웨덴 고교 흉기난동…극우 테러 모방 여부 수사

스웨덴의 한 고등학교에서 용의자가 흉기로 17세 여학생을 살해했다. 용의자가 범죄를 찬양하는 온라인 문화에 빠졌던 것으로 파악돼 당국이 극우 테러 배후를 수사 중이다.

**시사점** — 온라인 극우 문화의 청소년 급진화가 유럽 학교 테러로 번진 사례로, 모방 범죄 확산 여부가 수사 초점이다.

[극우 테러 따라했나…스웨덴 흉기난동 배후 수사](https://www.yna.co.kr/view/AKR20260823000700082)

### 캐나다 총리, 美에 보복관세 '맞불'…철강·낙농품 등에 부과 - 연합뉴스

캐나다 총리, 美에 보복관세 '맞불'…철강·낙농품 등에 부과    연합뉴스   Google 뉴스에서 헤드라인 및 의견 더보기

[캐나다 총리, 美에 보복관세 '맞불'…철강·낙농품 등에 부과 - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTE9Wdnh0emJGNnYtY1lsWVZNS29SX0sxTzYtVFZuUGE3UXlhT3BJQzZJQi03aGRnX3hHaEZBdnZQSjA5djJTb2J6WGw2Nl9ZcHUxbDhEMEV2bndWUzDSAWBBVV95cUxNSjhIaTN4N1d3bGtTNS1XN0RlLXB6UG5XT1VwcTZzQ0pXRU9HREVpTG1kMW9kc05LVkxNY3ZqbFhVTU5EM2w5akZ3aDBCemNUc01KNWFVOHBUel9iaXU0d2Y?oc=5) | [캐나다 총리, 美에 보복관세 '맞불'…철강·낙농품 등에 부과](https://www.yna.co.kr/view/AKR20260823000800087)

### 🆕 일본 지바현 가시와시 북동쪽서 규모 5.9 지진

한국시간 23일 오전 2시 0분 일본 지바현 가시와시 북동쪽 18km 지역에서 규모 5.9 지진이 발생했다고 기상청이 밝혔다.

**시사점** — 도쿄 인근에서 발생한 지진으로, 8월 일본 여행객과 지바현 체류자는 여진과 철도 운행 상황을 확인해야 한다.

[일본 지바현 가시와시 북동쪽서 규모 5.9 지진 발생](https://www.yna.co.kr/view/AKR20260823001300530)

### 이란, 이라크 유조선에 호르무즈 통과 특별 허가…"동쪽 해역 통제" 주장

이란이 이라크 유조선에 호르무즈 해협 통과를 특별 허가했다고 밝혔다. 이란은 호르무즈 동쪽 해역을 통제하고 있다고 주장했다.

**시사점** — 한국은 중동산 원유를 호르무즈로 들여오므로, 이란이 이 '특별 허가' 방식을 다른 나라 유조선에도 적용하는지가 원유 수급 변수다

[이란, 이라크 유조선에 호르무즈 통과 허용…"특별 허가" - 연합뉴스TV](https://news.google.com/rss/articles/CBMiZ0FVX3lxTE5kbV82TG1IWVRaY2hiM0xFMlZGc2xhZmp5STR6YU1PYWRwdm5zQ0JPbDM3Zk1jR19idWNsQUtCSXE0SmdoWDk5ZjRCVzVseGJTUldVUmlRYWxlZ1VKQ0FpQkZYbzNUZ1E?oc=5)

### 🆕 러시아, 북한산 미사일 50발 보유 추정…개량형 KN-30 포함

우크라이나 정보당국은 러시아가 북한산 탄도미사일 약 50발을 보유한 것으로 추정한다고 밝혔다. 여기에는 개량형 KN-30이 포함된다. 이 미사일이 흑해 곡물 수출 항로 타격에 쓰이는 정황이 거론된다.

**시사점** — 북한산 미사일 50발이 흑해 곡물 수출을 겨냥하는지가 국제 곡물가와 대북 제재 이행의 관전 포인트다

["러, 北미사일 50개 보유 추정…개량형 KN-30 포함" - 네이트](https://news.google.com/rss/articles/CBMiU0FVX3lxTE5KV0F6cU04OGhmN0x2MkJfNzFHTHNzYUxGdGU0cWVmOUEyam9xcDAwZkxOMUtTZWdNalBSWks4RXJNcXhqN19ZQjBiRURTSmNPcXNF?oc=5)

### 🆕 우크라 정보당국 "러시아, 북한산 탄도미사일 50발 보유·운용부대 배치"

우크라이나 정보당국은 러시아가 북한산 탄도미사일 50발을 보유한 것으로 추정한다고 밝혔다. 러시아는 이 미사일을 운용하는 부대를 배치했으며, 키이우까지 사정권에 든다고 전했다. 흑해 곡물 수출 마비도 관련 위협으로 거론됐다.

**시사점** — 북한 미사일 50발이 실전에서 소진되며 성능 데이터가 러시아를 통해 축적되는지가 한반도 안보의 직접 변수다.

[“키이우도 턱밑”…러, 北 탄도미사일 50발 보유·운용부대 배치 - 조세일보](https://news.google.com/rss/articles/CBMib0FVX3lxTE1lM0Q4eUZxRmp2anJKUEJpZEFuWTc1b3ZkOHpPTUFUb1ZzOGFOUXVkWVJUSUtBbEVKMnRYVmpMWTFJalFQUk02QnlOVXdWelZFeUtCazdubXNzMGlLQmdMT0tyNjVNak1zdG1GdmdUUQ?oc=5)

### 🆕 일본 정부, 내년 예산 1135조원 이상 요구할 듯…사상 최대

일본 정부의 내년도 예산요구가 1135조원(130조엔) 이상으로 사상 최대에 이를 전망이다. 4년 연속 최대 규모이며, 방위비 증액이 핵심 요인으로 지목된다.

**시사점** — 130조엔 예산에 담길 방위비 증액 폭이 한일 안보·재정 지형을 가르는 변수로, 연말 예산안 확정까지 주시할 사안이다.

[日 정부, 내년 예산 1135조원 이상 요구할 듯… 사상 최대 - 조선비즈 - Chosun](https://news.google.com/rss/articles/CBMingFBVV95cUxQVnJFTG9CNE5YMy1aRHl1d04xdVZscDdURlhSRDZqRzhmSS1lNWVRMFpLU3hOVWh4eldGeWNfRnB3NTZmSkdCR2MyZ0xYOWJEZjBaV0RITUtjVGkwd2VRWU9KeV9QZ3h3RUhINWhZV2pLb19JVFZSSkVTUXhxd1JyaVZkTkwzelBGc3NzQk5JNUNYX21BcjgwT21OQUFyZ9IBsgFBVV95cUxQQlZ0TTMxVE9oM2x3dnJ3Q2FjaGl1Yng3Q25sZlVWbTN4NFA5Z2tjSWV2aHExa0xjNlVlaldWSkljRDFQeWdtMGZsR0VoT2t5RThUbENCRnh4RVhGS3MtLTB4Ni1ESWlWUC1BWkg5b3RsdEx2QkhxdjZhWUJmT0Y5MlFPSlhFWkZZNm5LdnhPOXNucmJ6Rzg4bWZyWnJMMVpMcHNvOFV4eTRiSmVtcWY3ZjB3?oc=5)

### 🆕 미국, 중국 다롄 APEC 고위관리회의 참석…"미 기업 기회 확대"

미국 국무부는 오는 28일까지 중국 다롄에서 열리는 제3차 APEC 고위관리회의에 참석한다고 밝혔다. 미국은 자국 기업의 기회 확대를 참석 명분으로 제시했다.

**시사점** — 28일까지 이어지는 다롄 회의의 미중 무역 기류가 같은 APEC 회원인 한국 수출 기업에 신호가 된다.

[美, 中다롄 APEC 고위관리회의 참석…"美기업 기회 확대"](https://www.yna.co.kr/view/AKR20260823002100071)

### 캐나다 보복관세에 미국 재보복 방침…무역갈등 격화

미국과 캐나다의 무역 협상이 결렬됐다. 캐나다의 보복관세에 미국은 200억 달러 규모의 캐나다산 제품에 50% 관세로 대응하는 방침을 밝혔다.

**시사점** — 200억 달러 규모 미국 관세의 발효 시점과 캐나다의 추가 보복 여부가 다음 변수다

[캐나다 보복관세에 美 "대응" 방침…협상결렬에 무역갈등 격화(종합)](https://www.yna.co.kr/view/AKR20260823000651071)

### 🆕 이스라엘, 시리아 남부 공격…시리아 "주권 침해"

시리아 남부에서 이스라엘의 공격으로 1명이 부상했다. 시리아는 이번 공격을 주권 침해로 규정했다.

[시리아 남부서 이스라엘 공격에 1명 부상…시리아 "주권 침해" - 연합뉴스 한민족센터](https://news.google.com/rss/articles/CBMidEFVX3lxTE1mZW13TEw1VGRqNFZYaE4wcTVpYU44VGdKSUprOUNMc0RFMHkzQWxLR2duVGprYWZGelZyempFaWpnMWprNmRIX2hKaFVZdkxES0R2bmhqd3pSbmFacjU3d0g4WFBhQXpJcElPWXBzZHRKVVB4?oc=5)

### 캐나다, 미국 50% 관세에 맞불…카니 총리 '미국과 전쟁 중'

미국이 캐나다산 제품에 50% 관세를 발효했다. 캐나다는 다음 달 8일부터 보복관세를 부과하겠다고 예고했다. 카니 총리는 '미국과 전쟁 중'이라고 밝혔다.

**시사점** — 9월 8일 캐나다 보복관세 발효 전, 미국의 50% 관세 선례가 한국의 대미 관세 협상 조건에 그대로 옮겨붙을지 주시.

[카니 총리 “미국과 전쟁 중”···캐나다, 미국의 50% 관세 발효에 맞불 관세 예고 - ](https://news.google.com/rss/articles/CBMiWkFVX3lxTFBKTjROdnUtRGJxQkRxWElnaWpXMzFDU2xUMFFHcmFrUThkYWpaY1Q3YXBPZlJtMWJoSWNYQlZMTlpxZ1E0dEtfMDZaME5EZjZwWVkxUmNWay1qQdIBX0FVX3lxTFAtbkZabjJfb082by1XNkprWkpEcDJuYmpta1BDWGJMY0c5OExYVGpsUm96dy01c21HczhiNnprUW1MODlTRWctQ19IVUZpc29iY2dKQ1o1UDNYM096VElB?oc=5)

### 🆕 이번 주 뉴욕증시 최대 변수는 엔비디아 실적·PCE 지표

이번 주(8월 24~28일) 뉴욕 증시는 여러 대형 이벤트를 맞는다. 엔비디아 실적 발표와 PCE 지표가 주요 변수로 꼽힌다.

**시사점** — 8월 24~28일 엔비디아 실적과 PCE가 삼성전자·SK하이닉스 등 반도체株와 코스피 방향을 가를 이번 주 최대 변수.

[[뉴욕증시-주간전망] '베선트 풋'에 곤란해진 워시…엔비디아 실적·PCE 지표도](https://www.yna.co.kr/view/AKR20260823005500009)

### 🆕 미 공화 의원, 트럼프에 한미 연합군사훈련 복원 촉구

공화당 소속 리치 매코믹 연방하원의원이 한미 연합군사훈련 복원을 촉구했다. 그는 트럼프 대통령의 한미 연합군사훈련 축소 결정에 의문을 제기했다.

**시사점** — 매코믹 의원의 요구가 트럼프의 훈련 축소 방침을 되돌릴지가 대북 연합 방위 태세의 분수령.

[美 공화 의원, 트럼프에 한미 연합군사훈련 복원 촉구](https://www.yna.co.kr/view/AKR20260823004000009)

### 🆕 엔비디아, AI 서버 가격 15% 인상 예고

세계 최대 AI 칩 개발사이자 시가총액 1위 기업인 엔비디아가 고객사에 AI 서버 가격을 15% 올린다고 예고했다. AI 서버값이 이미 고공행진하는 가운데 나온 방침이다.

**시사점** — AI 서버 원가 상승은 HBM을 대는 삼성전자·SK하이닉스의 납품 단가 협상과 국내 데이터센터 증설 계획에 직접 반영된다

[AI 서버값 '고공행진'…엔비디아, 고객사에 가격 15% 인상 예고](https://www.yna.co.kr/view/AKR20260823016400075)

### ⚠ 日언론 '中, 필리핀 실효지배 세컨드 토마스 암초 점거 시도 가능성'

일본 언론이 중국의 남중국해 세컨드 토마스 암초 점거 시도 가능성을 제기했다. 필리핀이 실효 지배 중인 해역이며, 중국은 사실상 민병대로 운용하는 선박을 인근에 두고 있다.

**시사점** — 세컨드 토마스 암초 충돌은 한국 원유·컨테이너선이 지나는 남중국해 항로의 안전 비용과 미·중 대치 수위를 바꾼다

[日언론 "中, '필리핀과 영유권 분쟁 암초' 점거 시도 가능성"](https://www.yna.co.kr/view/AKR20260823018800073)

### 카니 캐나다 총리, 무역 협상 결렬 후 미국에 '전쟁' 선언

미국과 캐나다의 무역 협상이 결렬된 뒤 마크 카니 캐나다 총리가 미국과의 '전쟁'을 선언했다. 양국 관계가 파국으로 치닫고 있다.

**시사점** — 미·캐나다 관세 전면전은 북미 생산기지를 둔 한국 자동차·부품사의 대미 수출 원가를 직접 끌어올린다

[카니, 무역갈등 미국에 '전쟁' 선포…미·캐나다 파국 치닫나](https://www.yna.co.kr/view/AKR20260823017000009)

### 러시아 공습 이틀째…우크라이나 민간인 사망 70% 급증

러시아 폭격으로 우크라이나에서 이틀째 사상자가 속출했다. 민간인 사망자가 70% 이상 늘었고 도심이 큰 피해를 입었다. 푸틴은 우크라이나가 판도라 상자를 열었다고 경고했다.

**시사점** — 민간인 사망 급증은 협상보다 확전 국면을 굳혀 유럽의 대러 추가 제재와 유가·곡물 가격 변동성을 키운다

[러 폭격에 이틀째 우크라 사상자 속출‥민간인 사망 70%↑ - MBC 뉴스](https://news.google.com/rss/articles/CBMidEFVX3lxTFBUbGR0UTUxZ0t3T2kwT0ZWd1k3NzM3NldFWno5SXdGNDNQSlY1SHFFbEstbjVPNGlJQ2Jfa3o2UnNQbG04TUVwcDRHcWVmUzlZUFdTSExGVG1Kc3E2aWZKdldpOG9HdTk3SFVhbXZWQXBHVV9f0gF0QVVfeXFMUDZPNUNKS2ZPUzhRZkdsWTBZaVBhRFVYSDF2bHZWWjlSN3hRNlBCNWloSGJGOVJheWdSRDFwV2JSWFU3bFVRU2F6MG51MUl0cnRCQzhSOHJGYzR5VjBCS1hwclRxbnluWUgyeTNnQWw0U0dleFI?oc=5)

### 🆕 시리아 '이스라엘 공격에 민간인 부상…주권 침해'

이스라엘 공격으로 시리아 남부에서 민간인이 다쳤다고 시리아가 밝혔다. 시리아는 이를 주권 침해로 규정했다.

**시사점** — 이스라엘·시리아 충돌 확대는 가자 국면과 겹쳐 중동 리스크를 키우고 국내 정유·해운의 중동 항로 위험 비용을 높인다

[시리아 “이스라엘 공격에 민간인 여러명 부상…주권 침해” - 동아일보](https://news.google.com/rss/articles/CBMic0FVX3lxTE5XTUVVMzkwbEFSV25acFBlSE9yMGZuZVRaQXJKbXBIMWQ3RUdpX1k4STA5SFBvZy1sSDJGZ0FrTVNacWZFLTBNOUZUQ0xoWEppRGlyTUVKQ3JjRGZfSjQ1OGt2Qm5wYlcyTkUzOTlYbW0yS2vSAWZBVV95cUxPQmNSSDdGdUMxa1JremZFWC0yVlF4SnRJaFYxdExxX1doallMdW9TUVN3V3FPQ1pUcDVkaUlOVWNpM3BOcG5ZM0sxaDY3bnlQcHFyUlk5UVhsN0tLNV91c0toVFFocGc?oc=5)

### 🆕 푸틴, 우크라이나 ‘경제 공격’에 파괴적 보복 경고

푸틴 러시아 대통령이 우크라이나가 러시아 경제를 공격해 ‘판도라 상자’를 열었다고 말했다. 그는 파괴적 보복을 각오하라고 경고했다. 러시아 공습으로 우크라이나 도심에서 민간인 사상자가 이틀째 나왔다.

**시사점** — 러시아의 보복 수위가 우크라이나 종전 협상과 국제 유가의 최대 변수다

[푸틴 “판도라 상자 열었다, 파괴적 보복”…‘재앙’ 경고한 이유 - 서울신문](https://news.google.com/rss/articles/CBMid0FVX3lxTFBROG9OZ0lQeTUwRnM4b2ZSZDF2UHJsOEdSSS1wV2pKTGw5TGQxQTgyNlczb3pzaE9JRXNUVlBOV29mR19GSTM3WW93eGVMcXRJLW9ndU03ZElncnNhQmlwM2g3ZG5oRE91MmpvNWhPa0o1SWFOaVAw?oc=5)

### 🆕 일본 혼슈 동남부 규모 5.9 지진…도쿄도 흔들려

일본 혼슈 동남부 이바라키현에서 규모 5.9 지진이 발생했다. 도쿄 도심에서도 흔들림이 감지됐다. 일본 당국은 이바라키·도쿄 등에 강한 흔들림 대비를 경보했다.

**시사점** — 여진 추이와 일본 기상청의 후속 경보가 인접국 한국의 관전 포인트다

[“강한 흔들림 대비해야” 경보음…일, 이바라키·도쿄 등에 ‘진도 5’ 강진 - 한겨레](https://news.google.com/rss/articles/CBMiggFBVV95cUxOS0t2bDZJczJpM0xibXVmUHotUmtyVklTRi1hSkRRSWlLbUhoZnJSVHAxaV9vb3BWRzJYQ1pIWWIxY1lpbFZLZjd0VkpFR2FBYUpyOExiaFFqOXhBTTZ6cmluZ0VzVzlwcFpQczM3Y2Z0bEFzNGpSQ09Pb1RWNjNOVUl3?oc=5)

### 🆕 미 국채 금리 급등…베선트 재무장관, 재매입 확대로 진화 시도

채권 트레이더 출신 스콧 베선트 미국 재무장관이 국채 금리 급등에 대응했다. 그는 재매입(buyback) 확대 발표로 금리를 누르려 했다. 시장은 이 대증요법에 반발했다.

**시사점** — 미 국채 금리는 한국 시장금리·환율의 기준선이라 재매입 정책의 실제 효과 여부를 주시해야 한다

[국채금리 급등 '대증요법'으로 눌러보려다 '교육당한' 美재무](https://www.yna.co.kr/view/AKR20260823019100009)

### 국방부 ‘북한군 러시아 추가 파병 임박 징후 없어’

한국 국방부가 북한군의 러시아 추가 파병 임박 징후는 식별되지 않았다고 밝혔다. 다만 북한이 추가 파병을 준비하는 정황은 있다고 했다. 국방부는 북한 미사일의 실전 진화를 더 큰 위협으로 지목했다.

**시사점** — ‘우크라 3만 파병설’의 진위와 북한 미사일 성능 개선 속도가 한국 안보의 관전 포인트다

[국방부 "북한군 추가 파병 임박 징후 식별되지 않아" - 뉴스핌](https://news.google.com/rss/articles/CBMiXEFVX3lxTFBFYm9HUW5FUzhEc25GVlM0eVJJa0YtTElXUXZ3NGgxSlFTQU5WV19XSjd0eTNxcU9IZVl0a2FjVEhrRDhYRmZuY0w2eDRoNHl5VDYtSmVYVTNTaDU4?oc=5)

### 이란 ‘미 제재 동참국은 적’…중국 원유 구매가 표적

이란이 미국의 경제제재에 동참하는 국가를 적으로 간주하겠다고 경고했다. 미국은 이란에 전례 없는 압박을 가하고 있다. 이란산 원유 최대 구매국인 중국이 핵심 표적으로 거론된다.

**시사점** — 중국이 이란산 원유 구매를 유지할지가 국제 유가와 미·중 통상 갈등의 변수다

[이란 "미 경제제재 동참 국가는 우리의 적" 경고 - MBC 뉴스](https://news.google.com/rss/articles/CBMidEFVX3lxTE9UVzFaUVB6VjI0bWh2ZGZNN2J0OTA4OXZwcUhuZHR6RjREaVVOX0ZydWJiV3NWQUpHeDNTaU54dXMtb0ZpMlhHV1ZTejhLaTJBZzBINUhYWTNpbEo2Zzg1cWNLcjZxSUMzUlRMdHdKRjBoVjVY0gF0QVVfeXFMUFBVQURDSThVVFJTa0pES2RIZXNWLVg3dlg0VmQtckdCRHNYWVdKeXgzejRlLXR6YWM5eU1aT3N6RXRMY2ZscVdJd0NwYmp2QnNNMG5ia1ZINFJxNWFubXRfZFEyMHUtT0xCdVpZWndXS3hodFc?oc=5)

### 🆕 러시아, 북한 신형 미사일 KN-30 첫 확보…보로네시에 발사대 배치

러시아가 북한의 신형 탄도미사일 KN-30을 처음 확보해 보로네시에 발사대를 배치했다. 북한이 러시아에 미사일 50발을 넘긴 정황이 제기됐고, 우크라이나 방공망은 대응에 어려움을 겪고 있다.

**시사점** — 러시아 실전에서 검증된 KN-30 데이터가 북한으로 역류하는지가 한국 방공망의 최대 변수다.

['北 미사일 50발' 러시아 손에?…우크라 방공망 '속수무책' [자막뉴스] - 네이트](https://news.google.com/rss/articles/CBMiYEFVX3lxTE1pejIzN1J6Y3V6eDRzSUlIUXRPa3VMdWFmVUlhQ2MzX2xESGJtVXJNWkNiNENKTVBDbEJuTjZBM1FRVVdsQjJSM3pFanh2U0htRUFKdGFGa09CRGJVMnVKSQ?oc=5)

### 🆕 러시아, 우크라 쇼핑몰에 '더블 탭' 드론 공격…최소 16명 사망

러시아가 우크라이나 도심 쇼핑몰에 '더블 탭' 방식의 드론 공격을 가해 최소 16명이 숨졌다. 푸틴 대통령은 우크라이나가 러시아 경제를 공격해 '판도라 상자'를 열었다며 각오하라고 경고했다.

**시사점** — 민간 쇼핑몰 타격과 푸틴의 보복 경고로 종전 협상보다 서방의 추가 대러 제재 논의가 앞선다.

[러, 우크라 쇼핑몰에 '더블 탭' 드론 공격…최소 16명 사망 - 파이낸셜뉴스](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9xdjctS0ZGaW1JZEFLaVdFTHd3OHprNUxLTjdEMnJ5LUg3blRFMlNocmpIRlJVT1lwSG1iYWRGN29LYkJIUGZQMHh4cGZYSjJaT1pkbXJiQ0Rudw?oc=5)

### 후쿠시마 오염수 3년간 13% 방류…어획액은 사고 전 절반으로

후쿠시마 원전 오염수가 방류 시작 3년간 전체의 13%가 바다로 배출됐다. 같은 기간 후쿠시마현 연안의 어획 금액은 사고 이전의 절반 수준으로 늘었다.

**시사점** — 방류 진행률 13%는 한국의 일본산 수산물 수입 규제 완화 논의에서 핵심 근거가 된다.

[후쿠시마 오염수 3년간 13% 방류…어획액, 사고前 절반으로 늘어](https://www.yna.co.kr/view/AKR20260823022600073)

### 🆕 정부, 탄자니아 AI 사업에 1.7억달러 차관…한국기업 진출과 연계

한국 정부가 탄자니아의 AI·디지털 인력 양성 첨단교육기관 건립에 1억7천만달러 차관을 제공한다. 이 사업은 한국 기업의 현지 진출과 연계된다.

**시사점** — 1억7천만달러 차관에 연계된 한국 기업의 탄자니아 AI 시장 진출 성과를 지켜봐야 한다.

[정부, 탄자니아 AI 사업에 1.7억달러 차관…韓기업 진출과 연계](https://www.yna.co.kr/view/AKR20260822046000002)

### 🆕 일본 이바라키현 규모 5.9 지진…도쿄에서도 흔들림

일본 혼슈 동남부 이바라키현에서 규모 5.9 지진이 발생해 도쿄에서도 흔들림이 감지됐다. 도쿄 도심 슈퍼마켓에서 물건이 떨어지는 등 진동이 이어졌다.

**시사점** — 도쿄 도심까지 흔들린 규모 5.9로, 수도권 여진 가능성이 현지 한국 기업·교민의 당면 변수다.

[日혼슈 동남부 이바라키현서 규모 5.9 지진…도쿄서도 흔들림(종합) - 연합뉴스](https://news.google.com/rss/articles/CBMiW0FVX3lxTFBFMGdmNXBhVU9RM3dQWmVVV3hFWmRURGUyUkEybWpYczNBNU13aXltX1NVUmtRc2NsOURpOGNYaVk4STZrdy1JM0FsMnFTQ1ZOdmJoSHh4Zkt4MVnSAWBBVV95cUxNOUxfM2Z6SDdQZWdBMzY2MnlRQ19RRm5pTU5sNmZ2dTBfSnZIUFhCaGFaTWRKNmtSRzR6Y0ltVXhVWUgtSXE0MHdKbThZU3MzRll1ZFhTaDd1cHZEdjliVFk?oc=5)

### 🆕 소말리아 해적, 예멘 앞바다서 유조선 납치…4월 이후 6번째

소말리아 해적이 예멘 앞바다에서 유조선을 납치했다. 지난 4월 이후 여섯 번째 사례로, 올해 해적의 선박 공격은 13척에 이른다.

**시사점** — 예멘·소말리아 인근 항로를 지나는 한국 유조선·화물선의 보안 비용과 우회 부담이 커진다.

["소말리아 해적, 예멘 앞바다 유조선 납치...4월 이후 6번째" - YTN](https://news.google.com/rss/articles/CBMiXkFVX3lxTE1DVUxVMEluWnU1OEJEekFNenVTR1NJWmY3cHlXeUN0NURiaWtfaE44ME9qaTFjeWh6bnBkdFMtZUZqd0g0cF9IZlZWZS1hc2VKRE5DZjJZVmFid3ZvVHc?oc=5)

## 투자

**오늘의 분석**

오늘 시장을 관통하는 축은 미 재무부의 국채 매입 확대다. 19년래 최고였던 장기금리를 끌어내리자 비트코인·이더·지캐시가 두 자릿수로 튀고 금이 올랐으며 달러는 약세로 돌아섰다. 다만 분석가들이 이를 양적완화가 아니라고 선을 그은 대목이 핵심이다. 이번 상승의 상당 부분은 기록적 숏스퀴즈, 곧 하락 베팅의 강제 청산이 밀어 올린 것이라 펀더멘털보다 정책과 유동성이 만든 가격에 가깝다. BofA가 추세추종 펀드의 주식 노출이 이란 위기 이전 수준으로 복원됐다고 전한 것도 같은 위험선호 회귀의 단면이다.

이 유동성 랠리의 이면에는 관리되지 않은 틈이 함께 드러난다. 샌드박스 브리지 해킹, 토큰화 주식이 1960년대 월가의 종이 위기를 재현할 수 있다는 경고, 워싱턴주에서 막힌 칼시와 CFTC의 규제 공방은 제도 정비가 자산 상승 속도를 따라가지 못함을 보여준다. 관세 구도도 분배 문제를 드러낸다. 대법원이 관세를 무효화한 뒤 환급금은 먼저 기업으로 돌아가고 소비자 몫을 둘러싼 논쟁이 붙은 반면, 대캐나다 관세는 협상 결렬 직후 새로 발효됐다. 부담과 혜택의 귀착이 엇갈리는 국면이다. 실물 쪽에서는 엔비디아가 메모리 급등을 이유로 AI 제품·서버 값을 15% 넘게 올린다고 통보해, 자산시장이 정책 온기에 취한 사이 비용 인상이 이미 진행 중임을 상기시킨다.

앞으로 주시할 하나는 재무부 개입이 걷히는 시점이다. 매입이 잦아들면 금리와 숏 포지션이 되돌아오며, 이번 랠리가 유동성이 아니라 펀더멘털 위에 서 있었는지가 비로소 시험대에 오른다.

### Universal safety products: Director Ault buys $183,344 in stock

Universal safety products: Director Ault buys $183,344 in stock

[Universal safety products: Director Ault buys $183](https://www.investing.com/news/insider-trading-news/universal-safety-products-director-ault-buys-183344-in-stock-93CH-4872295)

### Texas Roadhouse CEO Gerald Morgan sells $3.03m in TXRH stock

Texas Roadhouse CEO Gerald Morgan sells $3.03m in TXRH stock

[Texas Roadhouse CEO Gerald Morgan sells $3.03m in ](https://www.investing.com/news/insider-trading-news/texas-roadhouse-ceo-gerald-morgan-sells-303m-in-txrh-stock-93CH-4872294)

### 🔴 국채 바이백 조정에 비트코인 25% 급등, 8만 달러 육박

미 재무부의 국채 바이백 조정이 비트코인을 며칠 만에 25% 끌어올려 8만 달러에 근접시켰다. 이 조치는 19년래 최고였던 장기 국채금리를 끌어내렸고, 기록적인 숏스퀴즈를 촉발했다. 분석가들은 이번 바이백이 양적완화(QE)는 아니라고 밝혔다.

**시사점** — 19년래 최고였던 장기 국채금리의 반락 지속과 숏스퀴즈 되돌림 여부가 비트코인 8만 달러 안착의 관건이다.

[How a Treasury buyback tweak helped bitcoin surge ](https://www.coindesk.com/markets/2026/08/22/how-a-treasury-buyback-tweak-helped-bitcoin-surge-nearly-25-in-days)

### 🆕 미국, 캐나다 무역협상 결렬 뒤 대캐나다 관세 발효

미국이 캐나다산 제품에 대한 관세를 발효했다. 양국 무역협상이 결렬된 직후 나온 조치다.

**시사점** — 캐나다산 수입품에 의존하는 미국 기업과 양국 교역 물가가 직접 타격받으며, 캐나다의 보복관세 대응 여부가 다음 변수다.

[U.S. tariffs on Canada take effect after trade tal](https://www.investing.com/news/economy-news/us-tariffs-on-canada-take-effect-after-trade-talks-collapse-4872296)

### 🆕 지캐시(ZEC) 48% 급등해 800달러 돌파…그레이스케일 현물 ETF 추진에 '차세대 비트코인' 기대

지캐시(ZEC)가 48% 급등해 800달러를 넘어섰고, 2018년 1월 고점을 웃돌았다. 선물 거래량이 수십억 달러에 달했다. 그레이스케일이 현물 ETF 전환을 향한 신청 진행 상황을 공개했다.

**시사점** — 그레이스케일의 현물 ETF 전환 신청 진행과 선물 거래량이 ZEC 추가 상승의 관건이다

[Zcash jumps 48% to over $800 as Grayscale spot ETF](https://www.coindesk.com/markets/2026/08/22/zcash-tops-usd800-for-first-time-since-2016)

### Vatican to build €100 million renewable energy plant, sources say

Vatican to build €100 million renewable energy plant, sources say

[Vatican to build €100 million renewable energy pla](https://www.investing.com/news/commodities-news/vatican-to-build-100-million-renewable-energy-plant-sources-say-4872308)

### U.S. judge strikes down immigrant visa suspension covering 75 countries

U.S. judge strikes down immigrant visa suspension covering 75 countries

[U.S. judge strikes down immigrant visa suspension ](https://www.investing.com/news/economy-news/us-judge-strikes-down-immigrant-visa-suspension-covering-75-countries-4872307)

### 🆕 우크라이나 드론, 러시아 온라인 소매업체 오존 물류창고 타격

우크라이나 드론이 야간 공습으로 러시아 온라인 소매업체 오존의 물류창고를 타격했다. 밤사이 진행된 공격이다.

**시사점** — 러시아 이커머스 오존의 물류 인프라가 표적이 되며, 전쟁 리스크가 소비·물류 기업으로 번지는지 주시.

[Ukrainian drones hit warehouse of Russian online r](https://www.investing.com/news/stock-market-news/ukrainian-drones-hit-warehouse-of-russian-online-retailer-ozon-in-overnight-strikes-4872310)

### 🆕 중앙은행들은 금을 어디에 보관하나

각국 중앙은행이 보유한 금을 어디에 보관하는지 다룬 분석이다. 보관 장소와 방식에 초점을 맞췄다.

**시사점** — 금값 강세 국면에서 중앙은행의 금 보관처와 보유 규모가 다음 방향을 가르는 변수.

[Where are central banks keeping their gold?](https://www.investing.com/news/economy-news/where-are-central-banks-keeping-their-gold-4872312)

### 🆕 이란, 이라크산 원유 유조선의 호르무즈 해협 통과 허용

이란 당국이 이라크산 원유 유조선 여러 척의 호르무즈 해협 통과를 허용했다.

**시사점** — 정유·해운주와 유가 민감 자산 투자자는 호르무즈 통항 재개가 국제유가를 끌어내릴지 주시해야 한다.

[Iran grants permission for a number of Iraqi oil t](https://www.investing.com/news/commodities-news/iran-grants-permission-for-a-number-of-iraqi-oil-tankers-to-pass-through-hormuz-4872318)

### 🆕 우크라이나 드론, 러시아 오존 물류창고 타격

우크라이나 드론이 러시아 오존의 물류창고를 타격했다. 러시아는 이날 대규모 야간 공격이 있었다고 밝혔다.

**시사점** — 물류 차질이 오존 실적에 미칠 영향과 러·우 확전 여부를 주시해야 한다.

[Ukrainian drones hit Ozon warehouse as Russia repo](https://www.investing.com/news/economy-news/ukrainian-drones-hit-ozon-warehouse-as-russia-reports-major-overnight-attack-4872319)

### 🆕 비트코인, 국채발 숏스퀴즈에 7만7천 달러선 유지

비트코인이 국채 시장발 숏스퀴즈 이후 7만7천 달러 위에서 거래되고 있다. 하락에 베팅한 숏 포지션이 강제 청산되며 가격이 밀려 올라갔다.

**시사점** — 7만7천 달러 지지선 유지 여부와 국채 시장 흐름이 단기 방향을 가른다

[Bitcoin holds above $77,000 after Treasury-fuelled](https://www.investing.com/news/cryptocurrency-news/bitcoin-holds-above-77000-after-treasuryfuelled-short-squeeze-4872323)

### 🆕 대법원 관세 무효 판결 후 기업에 관세 환급 시작…소비자 몫 논쟁

트럼프 대통령의 관세가 대법원에서 무효 판정을 받은 뒤 기업에 관세 환급금이 돌아가고 있다. 이를 두고 '기업 특혜'라는 비판이 나오며, 소비자들은 환급 혜택을 더 나눠 갖기를 원하고 있다.

**시사점** — 관세를 납부했던 수입기업이 환급 대상이며, 환급금이 소비자 가격 인하로 이어질지가 다음 정책 쟁점이다.

[A massive ‘corporate welfare’ program is underway ](https://www.marketwatch.com/story/a-massive-corporate-welfare-program-is-underway-and-consumers-want-a-bigger-cut-of-it-0ff06d67?mod=mw_rss_topstories)

### 🆕 비트코인·이더, '숏스퀴즈' 랠리로 하락 베팅 청산…머스크 X는 창작자에 스테이블코인 지급 추진

비트코인과 크립토가 수개월 만에 최강 랠리를 펼쳤다. 국채 개입, 규제 움직임, 역대급 숏스퀴즈가 겹친 결과다. 머스크의 X는 창작자에게 스테이블코인으로 대가를 지급하는 방안을 추진한다.

**시사점** — 국채 개입과 규제 움직임이 겹친 이번 랠리가 지속될지가 크립토 투자자의 관건이다.

[Bitcoin and Ether bears get decimated amid 'squeez](https://www.coindesk.com/business/2026/08/22/bitcoin-and-ether-bears-get-decimated-amid-squeeze-led-rally-and-musk-s-x-wants-to-pay-creators-in-stablecoins-crypto-week-in-5-stories)

### 🆕 중간선거의 해, 증시엔 의외의 호재…'선거 이후 강세' 역사적 패턴

미국 증시에는 중간선거 이후 강세를 보인 강한 역사적 패턴이 있다. 올해가 그 중간선거의 해다.

**시사점** — 미국 주식 투자자는 11월 중간선거 이후 계절적 강세 패턴이 재현될지 주시해야 한다.

[Here’s some surprisingly good news for the stock m](https://www.marketwatch.com/story/heres-some-surprisingly-good-news-for-the-stock-market-this-midterm-election-year-d492d3a4?mod=mw_rss_topstories)

### 🆕 재무부 발표에 이번 주 금·비트코인 랠리…달러는 약세

이번 주 재무부가 국채 매입 규모를 두 배로 늘리겠다고 밝힌 뒤 암호화폐와 귀금속 가격이 급등했다. 같은 기간 미국 달러 가치는 약세를 보였다.

**시사점** — 재무부의 국채 매입 확대가 이어질 경우 달러 약세와 금·비트코인 강세가 지속될지가 이번 주 시장의 핵심 변수다

[Why an announcement from the Treasury sparked a ra](https://www.marketwatch.com/story/why-an-announcement-from-the-treasury-sparked-a-rally-in-gold-and-bitcoin-this-week-d9d5972b?mod=mw_rss_topstories)

### 🆕 BofA '추세추종 펀드 주식 포지션, 이란 사태 이전 수준 회복'

뱅크오브아메리카(BofA)는 추세추종 펀드(CTA)의 주식 포지션이 이란 관련 지정학 위기 이전 수준으로 돌아왔다고 밝혔다. 위험자산 노출을 다시 늘린 상태다.

**시사점** — CTA의 기계적 매수 여력이 이미 소진된 상태라, 지정학 재점화 여부가 지수 되돌림의 최대 변수다.

[CTA equity positioning back to pre-Iran levels: Bo](https://www.investing.com/news/stock-market-news/cta-equity-positioning-back-to-preiran-levels-bofa-4872364)

### 🆕 예측시장 칼시, 워싱턴주서 서비스 차단…CFTC와 규제 공방

예측시장 플랫폼 칼시(Kalshi)가 워싱턴주에서 고객 이용이 차단됐다. 칼시는 법정에서 이에 대응 중이며, 연방 규제기관 CFTC는 새 규정 마련을 이어가고 있다.

**시사점** — 칼시의 주별 영업권이 소송에 달려 있어, 워싱턴주 판결과 CFTC의 새 규정이 예측시장 확장의 분기점이다.

[Kalshi off-limits in multiple states as prediction](https://www.coindesk.com/news-analysis/2026/08/21/kalshi-off-limits-in-multiple-states-as-prediction-markets-cftc-team-up-for-battle)

### 🆕 샌드박스, 해킹 후 베이스·BNB 체인 브리지 중단

웹3 게임 네트워크 더 샌드박스가 익스플로잇 발생 후 영향받은 네트워크의 브리지를 중단했다. 회사는 토큰을 격리했고, 이용자에게 베이스와 BNB에서 SAND를 거래하지 말라고 경고했다.

**시사점** — 브리지 재개 시점과 회사가 확정할 피해 규모가 SAND 보유자에게 가장 중요한 후속 변수다.

[Web3 gaming network Sandbox stops Base and BNB cha](https://www.coindesk.com/web3/2026/08/22/web3-gaming-network-sandbox-stops-base-and-bnb-chain-bridging-after-exploit)

### ⚠ 페어민트 CEO '토큰화 주식, 1960년대 월가 종이 위기 반복 우려'

페어민트(Fairmint)의 조리스 들라누 CEO는 토큰화 주식이 분열된 시스템과 표준 탓에 1960년대 월가의 '종이 위기'를 재현할 위험이 있다고 경고했다.

**시사점** — 토큰화 주식의 정산·기록 표준이 통일되지 않으면 마찰이 커지므로, 발행 플랫폼 간 상호운용 표준 마련 여부가 관건이다.

[Tokenized stocks risk repeating Wall Street’s 1960](https://www.coindesk.com/tech/2026/08/22/tokenized-stocks-risk-repeating-wall-street-s-1960s-paper-crisis-fairmint-ceo-says)

### 🆕 BitMart, 폐쇄 발표 몇 주 만에 부분 재개·채권자 변제 검토

가상자산 거래소 BitMart가 서비스 폐쇄를 발표한 지 몇 주 만에 부분 재개와 채권자 변제를 저울질하고 있다. 이 거래소는 구조조정 자문사로 로펌 White & Case를 선임했다. 상세 로드맵은 9월 9일까지 나올 예정이다.

**시사점** — BitMart 이용자와 채권자는 9월 9일 공개될 로드맵에서 자금 회수 범위와 재개 조건을 확인해야 한다.

[Crypto exchange BitMart weighs partial restart and](https://www.coindesk.com/business/2026/08/22/crypto-exchange-bitmart-weighs-partial-restart-and-creditor-payouts-weeks-after-announcing-shutdown)

### Putin says Ukraine opened ’Pandora’s box’ with strikes on economic targets

Putin says Ukraine opened ’Pandora’s box’ with strikes on economic targets

[Putin says Ukraine opened ’Pandora’s box’ with str](https://www.investing.com/news/commodities-news/putin-says-ukraine-opened-pandoras-box-with-strikes-on-economic-targets-4872370)

### 🆕 8월 시장 브리핑: 주식·채권·크립토·원자재

2026년 8월의 주식, 채권, 크립토, 원자재 시장을 정리한 월간 브리핑이다. 특정 종목 추천이 아니라 시장 개요를 다룬다.

[Monthly market brief: equities, bonds, crypto, and](https://www.investing.com/news/stock-market-news/monthly-market-brief-equities-bonds-crypto-and-commodities-in-august-2026-93CH-4872374)

### Iran condemns US plans to announce new sanctions

Iran condemns US plans to announce new sanctions

[Iran condemns US plans to announce new sanctions](https://www.investing.com/news/commodities-news/iran-condemns-us-plans-to-announce-new-sanctions-4872376)

### 🆕 파라마운트, 워너브러더스 딜 관련 예비 협상…NYT 보도

뉴욕타임스(NYT)에 따르면 파라마운트가 워너브러더스 인수 건을 두고 예비 협상을 진행한다. 아직 초기 단계의 논의로 전해졌다.

**시사점** — 예비 협상이 정식 인수 제안으로 이어지는지, 미디어·스트리밍 업계 재편의 분수령으로 파라마운트와 워너브러더스 딜 진전 여부를 주시.

[Paramount and California to hold preliminary talks](https://www.investing.com/news/stock-market-news/paramount-and-california-to-hold-preliminary-talks-on-warner-bros-deal-nyt-reports-4872384)

### 🆕 엔비디아, AI 제품 15% 이상 가격 인상 고객사에 통보 (블룸버그)

블룸버그에 따르면 엔비디아가 고객사에 AI 관련 제품 가격을 15% 넘게 올린다고 통보했다. 인상 대상과 시점 등 구체적 조건은 보도로 전해졌다.

**시사점** — AI 서버·데이터센터 사업자의 조달 원가가 오르며, 15% 인상폭이 하반기 클라우드 요금과 하드웨어 마진에 반영될지 주시할 대목이다.

[Nvidia customers notified about AI-related price h](https://www.investing.com/news/stock-market-news/nvidia-customers-notified-about-airelated-price-hikes-above-15-bloomberg-news-reports-4872385)

### 🆕 엔비디아 고객, 메모리 가격 급등에 서버 가격 15% 이상 인상 직면

보도에 따르면 엔비디아 고객들이 15%가 넘는 서버 가격 인상에 직면했다. 메모리 가격 급등이 인상 요인으로 지목됐다.

**시사점** — 메모리 가격 상승이 이어지면 엔비디아 서버를 대량 구매하는 데이터센터·클라우드 사업자의 조달 비용이 커진다.

[Nvidia customers face over 15% server price hikes ](https://www.investing.com/news/stock-market-news/nvidia-customers-face-over-15-server-price-hikes-as-memory-costs-soar--report-4872389)

### 🆕 캐나다 유니포어 노조, GM과 잠정 합의 도달

캐나다 자동차 노조 유니포어(Unifor)와 GM이 잠정 합의에 도달했다.

**시사점** — 이번 합의는 GM 캐나다 사업장 노동자들의 임금·고용 조건을 좌우한다.

[Canada’s Unifor union, GM reach tentative agreemen](https://www.investing.com/news/stock-market-news/canadas-unifor-union-gm-reach-tentative-agreements-4872388)

### Russia stocks lower at close of trade; MOEX Russia Index unchanged

Russia stocks lower at close of trade; MOEX Russia Index unchanged

[Russia stocks lower at close of trade; MOEX Russia](https://www.investing.com/news/stock-market-news/russia-stocks-lower-at-close-of-trade-moex-russia-index-unchanged-4872390)

### 🆕 독일 메르츠, 내각에 성장 촉진 개혁 가속 압박

독일의 메르츠 총리가 내각에 친성장 개혁을 더 빠르게 추진하도록 내각을 압박할 계획이다. 구체적인 개혁 항목과 일정은 후보 원문에 제시되지 않았다.

[Germany’s Merz to press cabinet for faster pro-gro](https://www.investing.com/news/economic-indicators/germanys-merz-to-press-cabinet-for-faster-progrowth-reforms-4872393)

### Mexican governor, indicted by US on cartel charges, requests leave again amid backlash

Mexican governor, indicted by US on cartel charges, requests leave again amid backlash

[Mexican governor, indicted by US on cartel charges](https://www.investing.com/news/world-news/mexican-governor-indicted-by-us-on-cartel-charges-requests-leave-again-amid-backlash-4872398)

### Motor racing- Palou claims seventh IndyCar pole of season in Washington

Motor racing- Palou claims seventh IndyCar pole of season in Washington

[Motor racing- Palou claims seventh IndyCar pole of](https://www.investing.com/news/general-news/motor-racing-palou-claims-seventh-indycar-pole-of-season-in-washington-4872400)

### Motor racing-Milei puts himself in the driver’s seat to bring F1 back to Argentina

Motor racing-Milei puts himself in the driver’s seat to bring F1 back to Argentina

[Motor racing-Milei puts himself in the driver’s se](https://www.investing.com/news/world-news/motor-racingmilei-puts-himself-in-the-drivers-seat-to-bring-f1-back-to-argentina-4872395)

## 미국 이민

**오늘의 분석**

오늘 소식의 가장 굵은 흐름은 행정부의 이민 제한과 법원의 제동이 맞물린 구도다. 75개국 비자 동결이 위법으로 판정됐고, 39개국 대상 USCIS 심사 동결도 연방판사가 차단했으며, 10만 달러 비자세에도 법원이 제동을 걸었다. 반면 H-1B 신규 수수료안은 백악관 검토를 통과했다. 행정부가 여러 경로로 규제를 밀어붙이는 동안, 사법부가 가장 광범위한 조치들을 되돌리는 양상이다.

이와 나란히 9월 비자 불레틴은 가족초청 문호를, 특히 인도발 신청자에게 크게 열었다. 그러나 서류상 '문호 개방'은 개별 심사 단계의 강화와 동시에 진행된다. 결혼 기반 영주권 검증이 높아지고, 과거 경미한 교통위반까지 심사 대상이 되며, 청문 없는 영주권자 구금은 대법원 심리로 향한다. 새 I-485 양식 의무화와 온라인 제출 검토 같은 절차 정비도 이 강화 기조와 결이 같다. 범주 차원의 완화와 개인 차원의 압박이 함께 커지는 셈이어서, 대기 순번이 앞당겨진 신청자도 마냥 안심하기는 어렵다.

취업 기반 경로는 정치적 표적이 되고 있다. 밴스 부통령의 외국인 노동력 비판과 H-1B 폐지를 요구하는 인도계 기업인의 발언이 겹치고, 여기에 수수료 인상까지 더해진다. 다만 H-1B 개혁론이 모두 배외주의는 아니며, 임금 하방 압력이나 제도 오남용 같은 구조적 문제는 폐지가 아니라 잘 설계된 규제로 다뤄야 할 실체가 있다. 인도계 신청자에게 가족초청은 전진, 취업·H-1B는 정체와 압박이라는 엇갈린 신호가 동시에 온 하루였다. 앞으로 주시할 하나는 청문 절차 없는 영주권자 구금의 허용 범위를 정할 대법원 판단이다.

### 2026년 9월 비자 불레틴, 가족 이민 문호 대폭 전진

미국 국무부의 2026년 9월 비자 불레틴에서 가족 초청 이민 문호가 크게 전진했다. 인도 출신 신청자의 그린카드 대기가 완화됐다.

**시사점** — 가족 초청 우선일자가 지나간 한인 신청자는 9월 비자 불레틴 확정 후 I-485 조정신분 접수 시점을 앞당길 수 있다.

[US Visa Bulletin September 2026: Big green card re](https://news.google.com/rss/articles/CBMi_gFBVV95cUxPd3djWVdsam1TZzU3NVVlVDZOQmxQVTl6TFRUQzkxdWhUWklBWmd2ajl6aXlVckdDQkdERkFFb0RvdEFIM0VjNURtMjZoMzFSV2NSaGdpX0lCM1hNT2lhbFZCLTRPV2NTZ1VpMUk4ejdYeldRZkYyOUNNNVpOdUNTaFBELW1SQmEtUndBOWl5TkU4SjNLdDlPWENpQ0lWYXdaRzhkblpLR2d2WHVtbldFWC15UWo5cnRIOHo4RUY3OWFHc3RSVE9fcWJReV9tbUpsWmpFeko5aWpRVXlVRm1nUEJkOGlqSUh1eUh1WG9kZkp3ZldOUXBRTThaSXZqd9IBgwJBVV95cUxPMXNmTEFXbVBLWkRtQ0ZOemRMbDBfcFlxYkhldnJlOGpLZV83OW1VaERVaUVrbm1ENnN6NDNfT0hiNFlEbFJfRXQ3UFVEWUVqS1d2TmNQcU1ra2oxY2RBLWVqME9yblhZSThJTkpEc2tzZjV2cFlNY1ZTcUloNUd6RW0yNEl6XzQ3N2hXM1k5YlZTRDBtQ0thc1pkTlEwT1FOeFdqcTJwNHJ1SEhYWG84VHFObVNtSnJKNU5PV0NOck5Qa1pqT2VDVW44ZGRId2ozLXg1TmFkVHNxTWxxUGk2Y2Y0eHBsdkFoMVlrR2tiZVFjOXA4NkVmd25Za0xnSEtNanVN?oc=5)

### JD Vance blames foreign labor and open borders for decline of US; netizens react: ‘H-1B is an America last program’ | Hindustan Times - Hindustan Times

JD Vance blames foreign labor and open borders for decline of US; netizens react: ‘H-1B is an America last program’ | Hindustan Times    Hindustan Times

[JD Vance blames foreign labor and open borders for](https://news.google.com/rss/articles/CBMijwJBVV95cUxOLXk5Rnd5eGFCOVQ3VmZGd1lFV0FibS1SbGhtUXl2T3RmOWc4bGZ3SnZiamd3WWQ5LXJjeG1xTVhtRlJpSU9IeTcya2tKdUZOckFNekdpR2tiTXgtVHBjeG1NXzZDeUpTSHlLVklXUFJOQWx4M3B0NVMwcy1CenEwNkNaTUdhNk84WUg4VmZnZ0R6UXdGU3VEREY4UmV0NnBLZDRJb05zSUM3dTFXMmFuanlPTVBRTzNiSFVvc0pUYmxidDgyd211ajRULU5GcHRYcFhTZFE5SVcyQjBVMno0ZjYway1yV0hhSTJoRDRxMUM1eTdXeVZ5MmN3ekt4bm51d0VEZXNSRU5PbGpFM0Vr0gGUAkFVX3lxTE45aVVzM05BbGlQX25QTFFKbjI3aWdzTUcyZTJrS1RVRC1FSTJUNEQtLV90aU56MGUzS0s5cDVqRUxaUVRMelNsak1QOWRET3BxcUxyQVBmejBlQmxWQ2FDajY5ZmxjOTU1T1hJOUpQMHlMUDZsNzFtM2duWnpKLWFLOHRjTFJQRmlCb2JVcXlTdUZmbE11ZlZRSnF3bHA1OVFTbVJOUkpXOWhaWWI2QVR5QW5ESGhLY2h1bWM4VF9kZGZxZTkzYWJCM1dtVzJQU2I2Q3JrTEZPQUdWZG56XzA4VlF0ZGI3Yl9zMF8td0xRN3ZaZVIybTVaUUlTLW5SdzNQU1l4enRqSmhSV2RoMGk4M3Bocg?oc=5)

### 🆕 USCIS, 9월 18일부터 새 I-485 영주권 양식 접수

미국 이민당국이 9월 18일부터 새 판본의 I-485 양식을 접수한다. I-485는 미국 내에서 영주권(그린카드)으로 신분을 조정할 때 제출하는 신청서다.

**시사점** — 9월 18일 전후로 조정신분 영주권을 신청하는 한인은 접수일 기준 양식 판본이 맞는지 확인해야 반려를 피한다

[US to Accept New Form I-485 for Green Card from Se](https://news.google.com/rss/articles/CBMimgFBVV95cUxOR1RmaGl4LVA1RDcxOE1tWlpCcVZFcmE4VWctQlp6RlgySnFwSEtRNWh2SE1CSU0xSHFsQjlWdmpKeWZZbXAyVnZ1eWgzMW9tOFpJZkxxbXRiVzgzaVozSlA4WHVCRVBqZWtFZUUzQmNMUWptVnZkNWJHOEw2SHVoZzNtbUJEUDVkWUlucC1LREdCYjlxbkt3a2d3?oc=5) | [US To Accept New Form I-485 For Green Card Applica](https://news.google.com/rss/articles/CBMi0AFBVV95cUxNMzJCcXFvRktuRFJKS0cxcTgyUjlDZnhGMUdmVE12NVU1Z3RCbFI2RWZRRFVieUxGSWJ2M0EzVEFDOWROTHFJOU5JdGwtbzBCYzhNR1FMc1VTalFGdDlqdnZycUtLTDJHVnotUkotS0U1a0dZSEVoVHR1X2NLeGg1Q1A1LXFSWlhBbHFyMzFybGNTUVhEdkxoTlhUUm0xOHBjTkdjdnE5aXZNQ2FRRndWZE51bV9uaTZwTUN6aW0yTFZYTG9pTWxhblh5V21zOFBo0gHQAUFVX3lxTE0zMkJxcW9GS25EUkpLRzFxODJSOUNmeEYxR2ZUTXY1VTVndEJsUjZFZlFEVWJ5TEZJYnYzQTNUQUM5ZE5McUk5Tkl0bC1vMEJjOE1HUUxzVVNqUUZ0OWp2dnJxS0tMMkdWei1SSi1LRTVrR1lIRWhUdHVfY0t4aDVDUDUtcVJaWEFscXIzMXJsY1NRWER2TGhOWFRSbTE4cGNOR2N2cTlpdk1DYVFGd1ZkTnVtX25pNnBNQ3ppbTJMVlhMb2lNbGFuWHlXbXM4UGg?oc=5)

### 🆕 USCIS, 이민 서류 온라인 제출 의무화 검토

미국 이민서비스국(USCIS)이 일부 이민 신청서의 온라인 제출 의무화를 검토 중이다. 특정 양식이 신청자에게 온라인 전용으로 바뀔 수 있다.

**시사점** — 종이 서류로 신청해온 한인 신청자는 어떤 양식이 온라인 전용으로 지정되는지 USCIS 발표를 주시해야 한다

[USCIS Could Require Online Immigration Filings: Th](https://news.google.com/rss/articles/CBMihwFBVV95cUxQTlUxWEtyYU5fOXR6VDdEc2JsY2hEVEFMS0NTTDFwdHUwX2Zkek0ydmZFR3p5aGJoSFg1cUFVeEFLd1lpaGlRZEczY2wtWUdOTFZPazNEdzdCeUFJbXdERDBLdERNSlM2TlVqT3NrWm5qZmJ2TVJFREEwYWxKT1VsQTZfLVJkTjQ?oc=5)

### 🆕 국무부 '75개국 비자 동결' 위법 판정

미국 국무부가 시행한 75개국 대상 비자 발급 동결 조치가 위법으로 판정됐다. 해당 조치는 이들 국가 국적자의 비자 발급을 제한해 왔다.

**시사점** — 75개국 국적 비자 신청자가 대상이며, 국무부의 항소 여부와 동결 해제 시점이 다음 변수다

[State Department’s 75-Country Visa Freeze Is Deeme](https://news.google.com/rss/articles/CBMipgFBVV95cUxOVFlGRGFXVERjWDlFcjQ4YndrUnZ3dFNUNXI4SzE5WFNyRVJLcFRSX2YzbXc0cFpLTjVtWFVoN1pxWnlkWktyRUNvSnM4bk5FdWMyVEtvMmctbkhTcW5LaXdtaGtWbHJ6SVFidHpRc25TbHEwUXB3NDA0SElHdHpPdmhuZmZMVVZCdmdMS2FwQkR2UkJFLXgyWFh6TEtBcFQ1REEzOFFn?oc=5)

### 2026년 9월 미국 비자 불레틴 발표…인도계 숨통, 단 단서 있어

2026년 9월 미국 비자 불레틴이 발표돼 인도 출신 신청자에게 일부 개선을 가져왔다. 다만 조건부 단서가 함께 붙었다.

**시사점** — EB 취업이민 신청자는 9월 우선일자 전진 폭과 함께 붙은 단서 조건을 확인해야 한다

[September 2026 US Visa Bulletin: Latest update bri](https://news.google.com/rss/articles/CBMi-wFBVV95cUxOMXhfY1hXeTBfV3BDT0lXZXpibU9YUzRYRTdwbVlMTXhRWFJmLWxudDMxdkRvai1tQ3pNNWEwWEV3WmFvQ0diaHpPZzVmQVpHcHRHOTBmSjJnblJZc05FU085YnhVSmhmREhrRVZYOXlKMUw1T25IVzVnT21JMHMyNzdpNXFtTDlNV0tHaHdJMjFtWUZfbWdmb0RtTWRmX1RkT1pNMkR3Q211M2M4R1RyR015YjhUSmNqSk12aTVpNE1DM0ZEVXUwZmxrVnA4QVZmRjBLSHhFanZUSjN1d2FISTV3UDBqbkhfQU9rcnhuLS1NdVNQN0xXVWxnWdIBgAJBVV95cUxQc0pjNnpsT3FMZ3RtSklVVjVEMkdRU082dXdDU3B1Zi02eEd0bHFsTmpDa1ByOW1YSUcyZVhIaWV6eXhTdjVwTUlDUWc1R0pSeU1sUU1HcVpqN2pmdEtVU3RWUWZkRjRjTDVIblh4Z2xHUXRvekdJbVJlZkdLYjBSRFgxYXNoTDFWU09zVjZmVy0zVnRwQUR4ZzBCWTE2Q3FXRU4teWNkRGVjY0JMS1E1YVVUVmFXZGs2RThIRzdfcmpuR0E0a0ZNZGhTTlVqNmxIdFEyWVA2NV8tcXlybEt0ZXRpWXpTRjNPTDVEc3Fmc1J1bUU0YmEyRG4xRmR6a1FH?oc=5)

### US Green Card Backlog Keeps Indian Talent In Limbo - BW People

US Green Card Backlog Keeps Indian Talent In Limbo    BW People

[US Green Card Backlog Keeps Indian Talent In Limbo](https://news.google.com/rss/articles/CBMikwFBVV95cUxPdFRWRzF4b21WbUp6bXlVamVYREZKMEFHR3p4UWxTVjVKam9BRDZWNk95dWk2aDI1Y0Q3YlV2LTUtZ2c0SXJHWnFtQUdlTGhFM2FPUHUzS0F2RUFzT3pUdkgxc2Jwa3FoaXBxRVdrMDdIcTlSSjJhZWVMV3lRSVZFUjlCWTM2Z3pYR3pUUG5MVHpsdkk?oc=5)

### US issues details of new Green Card rules coming into effect from Sept 18 - Babushahi.com

US issues details of new Green Card rules coming into effect from Sept 18    Babushahi.com

[US issues details of new Green Card rules coming i](https://news.google.com/rss/articles/CBMi0wFBVV95cUxOX2JkcmlGTXNoQjNtOHhjM2stZWdYcHpKVFBka0JCUXNxVEVGb2ZTcXdmZEZpczdwT0xkZ3loTXF5RnBzSjd3VFhMRG41RmNBV3VtbVQ0MjRhZlIxVjZlcHhVSlUxNVVGMVZJY3QzcXpPOW9wU1k3OEs5RjN2ODBhZktiT1BjMmNhY28tSFA2UFZzVGg0V2w5aE4xUWlHb2ZBYlhzRFp3SzlGenZBR1FNNWpqZlIxVGtJdjZJMWhCYXBmRVNaeXZmWjI1cVRzb2xEemc4?oc=5)

### 🆕 美 연방판사, 39개국 대상 USCIS 이민심사 동결 차단

미국의 한 연방판사가 39개국 신청자에게 영향을 주던 USCIS의 이민심사 동결 조치를 차단했다. 법원이 정부의 심사 중단 조치에 제동을 걸었다.

**시사점** — 39개국 출신 신청자가 영향권이며, USCIS가 동결을 재개할지 여부와 후속 항소 진행이 최대 변수다.

[US judge blocks USCIS immigration freeze affecting](https://news.google.com/rss/articles/CBMisgFBVV95cUxOUVEwTkZlWndINmJOd25EMDRRTld2NHE1RlBxRGdkV0lnc2ZDbU1Jb0EtbnZ0SFFxT2Z2S0FrcmwwUjl0dmV4QkRTM2J2VnBIMTFoZmpnRXh1bEFweVFWNnFHTWFfaHY5ZDJVZ3ZESmJBa2s4RFEwU212ZGQwdGw4YmpGb19CcmpnUDVnemNZcHpDMmFodUlzak16d1RTdE4xLVJfS2dEb2UxZ1ZLVDE5ZHRR?oc=5)

### ⚠ 신규 I-485 양식, 9월 18일부터 시행

미국 영주권 신청의 핵심 서류인 신규 I-485 양식이 9월 18일부터 효력을 가진다. 신청자는 시행일 이후 신규 양식을 사용해야 한다.

**시사점** — 9월 18일 이후 구 양식 제출은 반려 위험이 크므로, 조정신분(AOS) 신청자는 그 전에 신규 I-485로 갈아타야 한다.

[US green card applicants alert: New Form I-485 tak](https://news.google.com/rss/articles/CBMi9wFBVV95cUxQTU5nUWdpRmVhXzV3Si1MRHp1ZW94ZThSakdoMlNRY19RYlUtWlVobEszUVVmRkFKZ0FTM2drR3dBOFRmZDYtVi1zQnRMZ2luUEpQM3FJUlFKN285QjNBZmItQTFzV2o1MjhONHBBNlpmejFtUC14amphUTQ1MUd5Tk1KYjg1b2JDNlBzMDhod0s0MDBmNDIxeFEtR0hDekgzSVlpaFhzb1NhMVcydUN1UThDUlBlU090aHJQLUVzcENDb2o1aTY3WThRWVhLM25TTW92blJHTmlYY0E5anhBaEtTZ0ZESGhVNHVoWlU1OGxWWmV4NEI00gH8AUFVX3lxTE03MkhlRG1vbTNBeTB3alpQd1BZbldVbWtVdGVGbzYtM1l1THJFZ0lhWURTWFFCMmhrakl6QTJRYkVfQXl5SWxHZ3dMUE8zei1iYlVSTFRPZDJzZzVxVlhoWlNodXJacXBhVHZ6Tm1xV1JCeEs4dUtSa01vdUZWZlhYRlh2bFEwRFNaWHBTZDBGY2xpZGdmSUNWd0h5dHJ6M0YxUmcxdmowQm9ESFFGWWtMVWRRNTQ4SjAxM2p4S0JWOC15QUY1M2RQT2ZRUWpjdHFicDVIVmUyc1FXRWlnbERnTmZtTjNnNThORXVNaDFLT1F5cnItYUdtcHItTQ?oc=5)

### 美, 결혼 기반 영주권 신청 심사 강화

미국이 결혼 기반 영주권 신청에 대한 심사를 강화한다. 심사 당국이 혼인 관계에 대한 검증 수위를 높인다.

**시사점** — 결혼 기반 영주권을 준비하는 한인 부부는 인터뷰·서류 심사 강화에 대비해 혼인 진정성 증빙을 미리 보강해야 한다.

[US Tightens Scrutiny on Marriage-Based Green Card ](https://news.google.com/rss/articles/CBMiowFBVV95cUxOX2NoN3hFVno5dnYtWkxiNlJSSEktUUpoMEU5X0VtREpSVGxGTFBvTkQzYnFLaVVnRnEtMFJnWDd0eUZ4WFBmcmlUWXpQT0tSTkpUUzR5SHZWWHZxNVBHTWZMbWRRY2hFVjVNMXBmejZsOExERXNJYW80OU0wSFBkNE5MQkl4WDdIcHdvb1o3eFlCek41SG84VThsSVBGUWZwcU9B?oc=5)

### Witchcraft Lessons While I Waited for My Green Card - wildhunt.org

Witchcraft Lessons While I Waited for My Green Card    wildhunt.org

[Witchcraft Lessons While I Waited for My Green Car](https://news.google.com/rss/articles/CBMijgFBVV95cUxNOG15cXBRUWxTMDRyMVcxdnkyM3Vibk9KczJyTm5SY2h3S25zQURrVnMwc193dXNYWHdHLUhJajNQemxOcF9UN09yOEluNzhMNDdqUk8xcnpzcmk3eDM4VFNNY3JzcG1seTFJbzlYdzRabXFKaFBBc0lvMzN0Y2lmMUdVMmtSVm9kMzd2aUFn?oc=5)

### US Outlines Two Important Benefits Available to Green Card Holders - Tuko News

US Outlines Two Important Benefits Available to Green Card Holders    Tuko News

[US Outlines Two Important Benefits Available to Gr](https://news.google.com/rss/articles/CBMipwFBVV95cUxObEZKYTNpckZ3TFo4WUJWWnZuM0hSYzhaMmJnSS05Y3c1VzhzU3c5MW04WHdNbHd3T3cxR1E0SUNpTkstUU11SXlyTC1ESkFRZDFiYzZ3cl9oYVBMTWhOVDEyaFR3cE92a3lfT0tILWpiaUt4YTNwb1VNUTZKS1Y4bFM1VUZSWExBa2cyRnNHamFfckJwMS00MmlvQU9kUS1ZSGJCcWNRQQ?oc=5)

### ⚠ USCIS, 9월 18일부터 새 영주권 신청서 양식 도입

USCIS가 9월 18일부터 새 영주권(그린카드) 신청서 양식을 도입한다고 밝혔다. 신청자는 해당 날짜부터 바뀐 양식을 사용해야 한다.

**시사점** — 9월 18일 이후 접수하는 한인 영주권 신청자가 구 양식을 제출하면 반려될 수 있으므로 새 양식 판본을 확인해야 한다.

[USCIS to Introduce New Green Card Application Form](https://news.google.com/rss/articles/CBMirgFBVV95cUxONTd2YjJDaC1VaDRYUWRBcEFWSGRnN09CcDZ3UTZMQWItdmdJQmIweXZYVW5SMVRlSVVwNTh5WFJkVVlra2V4NlJBRDJWeXFLb2lCX2dubTZDWEhzVlNMMWtDWUt5dWh2V09iUGRkM3R6V2lXbWRGRnpOVjIyRkRiaDVSLVZadDRwSlZxeXN1MVhpQmE4ZGVfZ1Y4Q3pKNXJMLXFxeEtrZnY2cnI3WkE?oc=5)

### 🆕 2026년 9월 비자 불레틴, 인도 가족초청은 전진·타 범주는 정체

2026년 9월 비자 불레틴에서 인도발 가족초청 영주권 신청자의 문호가 전진했다. 다른 범주에는 개선이 없었다.

**시사점** — 한인 가족초청 신청자는 같은 9월 비자 불레틴의 우선일자를 확인해 접수 시점을 맞춰야 한다.

[Good news for family-based Green Card applicants f](https://news.google.com/rss/articles/CBMipwJBVV95cUxOQ3RXcVdGVEtYNjFyXzRfcXl6OUNqRmhybkFWWkpWNTFBNEMxQVpHcVc2aGlhYTRBWFFVVE1OdV9sVjlSajNPeVBUaTBzSHI4b2xiS3AzaXBuRm9kM0RXbG5wa0U0dDdjMVJTTENTdUM4b193UGx4ampOUjJvWFhkTTNtZ184WDN3NTdUWG9hT0U5QURWR1B1c1o4Z05KUEt0akwtZTJ6Rkk3dEF1TTRVdlZKaTRXYkFyMEttVFlDdGhoVXpmX2p0OWRUejVsdkVPWFREWjktbXJuTmtqeFI5OFVIMDhERXJ5TkFoM1lMcVdPa3VsQjd0TlZIOHpuRC1kelhXdjVuYmFOYkJBdjJ4NXgydXNIY0psNWtnVHhZZjAxQ2NtWmhF0gGsAkFVX3lxTE8tU2xiSmEzMnlNSVhsbzRfSnpiVVp2X19kVVA2VlBNYmRBcHZmY0R2Wk0wWFI0cVRCbEVIZDZrZnhTS0UxS3k0czNxbHNFTFZfXzN6aE1DdmRfcjBpQ1RyUHBsWDA0WFhxT2tublFyU0c5NktlQVNpcmRwRVpDYjBlcUNKNnJuR0FVamRpS2NMSGZpMHlpRUJCSVN5dmdrVkJaT2l4dV8yZWs0YzhqUk9aYkxKeGEzSHVuenhJZlg4LWJyelBxOXRmajNnQkJVbDVOWnlxQXZ0djFEa0EzTFN3QTFyVU9ubGRBQVR4eDItaFl3TG1yZ1NrUjZBV0xPd1NSV1BSUVRuNURSQll3S0Z1UXJoY2NqVXNnb2g5N2V0SHc4WTRnVVZsMGp5bw?oc=5)

### 🆕 밴스 부통령, 일자리 공약서 외국인 노동력 겨냥

밴스 미국 부통령이 일자리 관련 공약에서 외국인 노동력을 문제로 지목했다. 미국 내 일자리 우선 기조를 외국인 근로자 규제와 연결하는 발언이다.

**시사점** — 미국 취업비자로 일하려는 한인 구직자는 밴스 부통령의 외국인 노동력 규제 발언이 향후 H-1B·EB 정책으로 구체화되는지 주시해야 한다

[Vance targets foreign labour in US jobs pitch - Ed](https://news.google.com/rss/articles/CBMigAFBVV95cUxOUHVwMzI1cGJZOTMzdkNwY2tybllIbWFyeldUU0g3cnZCQ3dMMTFSOGdvWURsb01oczZvZEw0eWpjWndNVGtQaExBRVc4dV9WUnIzaXZCclR2azVNUFJlTjkxZklKWTJaN3FleW9LR09NSUxZaExzcjZ6UVBMQ2NTY9IBjgFBVV95cUxNX0dpTkh4ZnFCTTRUTDRVbDlfLXZITlhoSlNvVGxaX3NqdTdxVTd3TVJQZ01IWXhkblV3WGd4U2RSNmNfb2tpZlYwekhMdmVlRmxONmtxbU5FM2tMYm5jbEhNdGZVSHpZVFY2MldRM2J0U1RTeHJjU1lSdEVXekNLaEJkMFY3NGN0TV9zQ3JB?oc=5)

### H-1B 신규 수수료안 백악관 검토 통과…법원은 '10만 달러 비자세'에 제동

H-1B 신규 수수료 인상안이 백악관 검토를 통과했다. 동시에 법원은 10만 달러 규모의 비자 '세금'(tax) 부과에 제동을 걸었다. 두 조치는 별개 절차로 진행 중이다.

**시사점** — 한인 H-1B 고용주와 신청자는 신규 수수료안의 확정 여부와 10만 달러 비자세 소송 결과를 함께 주시해야 한다.

[New H-1B fee plan passes White House review as cou](https://news.google.com/rss/articles/CBMiyAFBVV95cUxPdHIxOFViZktXSThDY3B6ZUZYb0JINmtXYlVVMXIwUjdIWjhWdHJsdDZMRkdWWFR5S0k3YWVyVGxjUGhuMmt4b1FUMU1xZ2VvV0k3MG5YTjFCWXlOeWdkamlDZ3k1SlI4NTMtd1hNMDd0TlpaZWZ2aGN1dUlmY3ZBWDBQVElDZFBmblpRQ1d3SHRpZW93UmkwVTBVeW0xZ1RjNUoyZ1Vrd3FEVDU0T1dyXzRURldsVUJXZmRFVTVfX0pfMmd4SGpSZNIBzwFBVV95cUxQaTh2dU45Z2FPQ3hOc19TV3h5cGNkTVlSNzZGQm5JMG10U0ZhQjdUcThVdkxPcWczbU9PSlVWVE9qTjVGOEpoNXdMN3h2TVptSl9yeTJxMThmMldlckhOVXNjZ3duc2NRREsybzUxbjlKMnUxRkF4THlqMTVsaDEwQmdWcmtHVlhtVXpNVzR4WVlRdWlpTGh2eXFTQlBKRmRIV3B6YU9kYWREYzZ1LU9RY3pDdEJHYWlYUTlrU1oxLXJDcWNyMkJjR1pTX1laZDA?oc=5)

### USCIS, 그린카드 핵심 양식 변경

USCIS가 그린카드(영주권) 신청에 쓰이는 핵심 양식을 변경했다. 이 변경은 두 곳 이상의 매체가 확인했다.

**시사점** — 그린카드를 준비 중인 한인 신청자는 접수 전 변경된 양식의 최신 버전을 확인해야 접수 거부를 피한다.

[USCIS changes key Green Card form - IBTimes India](https://news.google.com/rss/articles/CBMidEFVX3lxTE1jRkdvbWxONHdUZjE2cjhXcnM5ZTdyU1VLTHlIblZ4Z0FMb2YzRkZTYWRveWZXNUZ6YWxSaEZqNDhoSjd5Z3ZiV1NPVENsMWVnenhXLXoxMDYtM1RYNDFNQm1URWs0ZWtaeXV5VVBEUTFvWVNi?oc=5) | [USCIS changes key Green Card form - lokmattimes.co](https://news.google.com/rss/articles/CBMiggFBVV95cUxPazhLa19sekMyMjRaaVlBN1FBTXNaV3NNQUEwQW4wX0VRUXJFekJGU0NPXzVUSEd3Q25wZlhxVmxHZTY3MkVkUFJkX0tKRmh2eGNYS1VGYzRTZnlNNG1rbVZjUlN2RzlwVXJ5Z1ZXWlJ0MTdnNFltdDN4d0VDZmtUZEVR0gGHAUFVX3lxTE9CdW8tcjFKdGVybG8yYjlBTWVENV9vaWZQMU0yUkdtcndIUHBVbUNDYVpFT3gwZXlZS2RNTlFxLXRKZVJBdFBubjd4ekp4MjEtZm1YbUpPVThoYmZONW5zYWphZmhQejJWZFVrYm9BN3h2MDU4RnJHem5OX1BUUXNZcWFSUGJXMA?oc=5)

### 🆕 미 연방대법원, ICE의 영주권자 청문 없는 구금 기간 심리하기로

미국 연방대법원이 ICE가 영주권 소지자를 청문 절차 없이 얼마나 오래 구금할 수 있는지 판단하기로 했다. 이 사안은 영주권자의 무기한 구금 가능성을 다룬다.

**시사점** — 한인 영주권자도 재입국·구금 대상이 될 수 있어, 대법원이 구금 기간 상한을 인정하는지가 핵심 쟁점이다

[Supreme Court to Decide How Long ICE Can Hold Gree](https://news.google.com/rss/articles/CBMisAFBVV95cUxPMGlVa3VlRlF4aUVsMFR2Q2pGRlVHUnZ6NHVKTXUwenJDc0ZUMFlZQ2hNQTE1SldOLWl1WkVNcllvUXJEc2l5aE1MNTdSNkhQOXV0SWI4VHN5dDF0ODdWNXUzSU9xTmRYODRycmg3R0RmcFRYX1lOblpzYmlPbW9vdVF3Y05Oek05ZjA4WVN6VVE3Y0FUSW8xallRWmFKa09oZ0s5RUkzbHVhZ2UzWkhRVg?oc=5)

### ⚠ 새 I-485 양식 9월 18일 발효…영주권 신청자 확인 필수

미국 이민서비스국(USCIS)의 영주권 신청서(I-485) 새 양식이 9월 18일부터 효력을 갖는다. 인도계 등 영주권 신청자는 이 양식 변경에 대응해야 한다.

**시사점** — 9월 18일 이전 접수를 준비하는 한인 조정신분 신청자는 제출 시점과 사용 양식 버전을 반드시 확인하라

[New I-485 Form Takes Effect Sept. 18: What Green C](https://news.google.com/rss/articles/CBMickFVX3lxTE1peTZtWjl0OWdxOWRLZ3hHQUtOQ3VDakFnUkhLR09xSzBlQ0pvNV9pbXVFZElwWThvOVpqME5RNDVwWVJTV1B5a2FVQ3AwQWdRcVBfUmtfUzJXUnQ2YnFneTd0US1mTTdQb1Z6alplclpGZw?oc=5)

### 🆕 워싱턴 연방지법, 국무부의 75개국 이민비자 발급 중단 심리

워싱턴 D.C. 연방지방법원이 국무부의 이민비자 발급 중단 조치를 다뤘다. 이 조치는 75개국 신청자에게 영향을 준다.

**시사점** — EB-5 등 이민비자 신청자는 자국이 75개국 중단 대상에 포함되는지, 법원이 중단을 유지할지 확인해야 한다

[D.C. District Court Addresses State Department Imm](https://news.google.com/rss/articles/CBMiyAFBVV95cUxNM3gxdnpGbnJYc2tFNzRvQWtOM0hObWVWWDRJQmNXUk1kQWtoRjFpektmaEQ2YXE4R01wZTZxVUdJMWN5RGo5VWRuU3F5M3c2LU45emIwNGgtVWQ2Ni1DZ0JSQlBEZDQ4NGszck9fd2NNUUhUQmxZazNLQWpoSFU3NzdMeUNlR0xFTm9xNE92cjNEMzR4VDd2T2FIZC1Qc29tWVF3OFRsNkVwMzhZVUEzNU9SZ2lEQzU1UnNVa0ZZa3dPeG5ZdU83Zg?oc=5)

### 🆕 9월 미국 비자 불레틴, 가족초청 계열 우선순위 날짜 큰 폭 전진

미국 9월 비자 불레틴에서 가족초청(F) 계열 카테고리의 우선순위 날짜가 크게 앞당겨졌다. 국무부가 예상보다 넓게 문호를 개방한 것으로, 대기 중이던 신청자의 심사 순번이 앞으로 당겨졌다.

**시사점** — 가족초청 영주권을 기다리던 한인은 9월 우선순위 날짜(PD) 전진 폭을 자신의 접수일과 대조해 신분조정(AOS) 신청 시점을 앞당길 수 있다.

[U.S. September Visa Bulletin Shows Major Advances ](https://news.google.com/rss/articles/CBMiqwFBVV95cUxQM0lRZjZsOHJ4V3lucnpkRU1Nc01LcDNmOVVBSkhEcE9iUlhzWUp4RDk3SVBtVnpuQk9PZ0JhT2N0UWloNUFabERrbVZKUTUyaGVtQzhnU05DRHFUN1FiSWZxUDVMN3gxemFxS1BxUzBPbWRQQVhCcWtLUmNXbS1OcTRQTUEwT25UdUtDQVJvWnF1Q3p4bXVVV19pOVAtNDJjMVppX29nRUI2WWc?oc=5)

### ⚠ 그린카드·비자 신청자, 과거 교통위반 등 경미한 위반 기록도 더 엄격히 심사

미국 영주권과 비자 신청자에 대한 심사에서 과거 교통위반을 포함한 각종 위반 기록에 대한 검증이 강화되고 있다. 과거에는 문제되지 않던 경미한 사안까지 심사 대상에 포함되는 추세다.

**시사점** — 과거 경미한 교통위반이나 법 위반 기록이 있는 한인 영주권·비자 신청자는 법원 처분 기록과 벌금 납부 증빙을 미리 확보해야 한다.

[Green card, visa applicants face greater scrutiny ](https://news.google.com/rss/articles/CBMitwFBVV95cUxPX09DTE9UNENGUWNJU3RMVzIyeU5iSS1zdm9HaTFzX1R5VHJBTHdIb0cwdklsZ2JGRklBQXUyVXlSTUJQNFgzM1ZLNjhEd2tYMUJQYlNpWVJzcm9xUjFYX25SeW96VTZ1b0xNYXItVmdkdkVTZ2l5TGJEcWJJMElSb2JTdDlCTzc4OERBTnZEYnE2QnoyVkxXQ0xNN2RHX29tdlAtUnQ2aElUNWszN185dEktd2IyQXM?oc=5)

### 🆕 연방판사, 트럼프 75개국 이민비자 동결 무효화

연방판사가 트럼프 행정부의 이민비자 금지 조치를 무효로 판결했다. 이 조치는 75개국을 대상으로 한 영주권(그린카드) 발급 동결이었다.

**시사점** — 트럼프 행정부의 항소·재지정 여부가 75개국 영주권 신청자의 발급 재개 시점을 좌우한다

[Trump immigrant visa ban overturned: Federal judge](https://news.google.com/rss/articles/CBMiwgFBVV95cUxPTmE2b3Z3d0dSNlpWSjFraTBLN09zdDh4eW5kZVE3bU0wU2JuUUZ2aVFxaHc1S21ReGxvel9RSXRsQTV1Rmd4LVZHamtBd1BERXhucmVmM0NGU0JCazVoMGxWbU9pa2I1TXkzNmxPNngxMV9pMXlyS2hUaTJKXzlzeEs2S1RBcHoxYnY1LS05ZXdKNXNLd1REaUZ3YWdFY254NkpuTEkwakJMVGJpYm9lcEN5Y1VyamhqZUEzOFZPT3ptUQ?oc=5)

### 🆕 그린카드 신청서 새 I-485 양식, 9월 18일부터 의무화

미국 이민당국이 영주권 취득을 위한 신분조정 신청서 I-485의 새 양식을 9월 18일부터 의무화한다. 그린카드 신청자는 이 날부터 새 I-485 양식을 사용해야 한다.

**시사점** — 9월 18일 전 접수를 노리는 한국인 그린카드 신청자는 구 양식 마감일과 새 양식 발효일을 대조해 제출 시점을 정해야 한다.

[Applying for a US Green Card? New Form I-485 becom](https://news.google.com/rss/articles/CBMi0gFBVV95cUxPbWRTdWhHOVFCWms0YXVXeXRQY0FjTnNNTHFoNVhOVlpxdl81emh6MnJ4ZlpsN3pzS3lQMTNHUERCcWxSdDFHQ196RFRuRlY3YVlDOG5jVWpJUWtwQmtBUjU3a0lfbm8yRTdqU1d6RHlCdndYYngxdmw2QV9hRzBVT05zckRnQ2Q2OU5yY0ZlOWNkS3B2dFZDVW1ZblgzSWhFUHh0dnBZYjJ6MURwVXhsT01wRHgwLXRMX3VJRGtOQWRWOEg3cDBzNTVkblczZGRkZnfSAdcBQVVfeXFMTWZjV2VoV1BLcHlKMnFjUnJLWFB6dEV2dFVYR1VJZTBqcXhMa0xXZ1d0dE8zOXgwbFNmSE1zLUFPdHQ0Ni1NanAySnE1RWRXNHpWVGZLUWFkNm5yazhPaXRDSENxcWhQdFpnaTFaSVBIMWRkUF9VVkhyWEZNSTNyUm53ME8yOFdjOEtnODlpQ2lrT21FaGVaSndacFRaTFhnejhLUG1kY2dzYVpYTnBCeFhNanhPNW5QTzBIYWpOTjk1TWlxWnR4T1E3ZmdFbjg5dDN3bFMzaG8?oc=5)

### Green card holder detained by ICE after immigration judge dismissed her case - Modern Ghana

Green card holder detained by ICE after immigration judge dismissed her case    Modern Ghana

[Green card holder detained by ICE after immigratio](https://news.google.com/rss/articles/CBMiX0FVX3lxTE94WDB5Y0l5V2VTTTlTSkpfRnNhX1BLaDl6SjBHQk4yaHJqZkswUGJ2dVF4bWJieVk5Y1B5bGQwWFFjRFNXcjV5U0g3dFRRVDRUWTJfZE1xX1BodVdqdmlN0gFcQVVfeXFMTkV2b1RKMFktUXMxakFZWlBkYjNJZjI3d21ISEFBbTl1ZVdZWm9hVWJFcTF4c3AxREhyanVlU2lJX3I0c2s2azBNSHlCcHNXT2JqTkpBTjE5Rmc2cUs?oc=5)

### 9월 USCIS 비자 불레틴: 가족초청 날짜 전진, 접수 차트 확인 필수

2026년 9월 USCIS 비자 불레틴에서 가족초청(Family) 카테고리의 날짜가 전진했다. 신청자는 접수 차트(Filing Chart)를 확인해야 한다.

**시사점** — 한국 가족초청 이민 대기자는 9월 불레틴의 접수 차트(Filing Chart) 사용 가능 여부에 따라 이달 서류 접수 시점을 결정해야 한다

[USCIS Visa Bulletin September 2026: Family Dates M](https://news.google.com/rss/articles/CBMilAFBVV95cUxNTU1Ma0t5dEdRdkF4ZHhabEZ4cFRldElPRFVPV3hwbXRLQ1RSbXk2ZWppU0FUX3RjRUNyckNzUlFUcy1nVVAxVEZfUzJuUXZWTlZqWjhJVnJoTjdSekdzS0pZQTcyam13bER5RWZPVXByY0d5NzlRZU5MbGk1TmNxN3JYMVlqcnhlMjIzOGZQZy03dlRG?oc=5)

### 🆕 미국 이민 주요 일정 7건…유학생·H-1B 근로자 필수 확인

미국 이민 관련 주요 일정 7건을 정리한 자료가 나왔다. 인도 유학생과 H-1B 근로자가 챙겨야 할 비자·이민 절차 날짜를 담았다.

**시사점** — H-1B 근로자와 유학생은 이 7개 날짜를 놓치면 신분·체류에 차질이 생기므로 각 마감일을 캘린더에 표시해야 한다.

[US immigration calendar: 7 key dates Indian studen](https://news.google.com/rss/articles/CBMiwAFBVV95cUxNajBEVnVXZ2pWdWI4WHNHUWxVWlVzUnpYaE01RkQ3Vk5yZEJ5WmF3bDUzQVFINld0MzBSUk5KektyLXVILU5fY3p4OUtLTWxqdWNLTmRlT0pCMEljaXRkcTd1WFc4UEhRazZ6dzU4anMzd3pPaTVZOGJPY09CNDBQUGVpbnVPMERmVVNKc0hncXFFOUg3RTZ2Vjc3OXFZSzVXNnBDVDhnM1VfaUhHaS1SdExpU3BuVFVsdWtKMFpCWU7SAccBQVVfeXFMTUtVMGZJUkgtbFRkVDFMSFdjNFhWQ0VabjJIUWdDdUNJdHEyN20waU5ORkpaaWxzMGlHeW1FTGw1QUx2YnhGNmIycWo1ajRLV3lmZ01mVU82TG1oc1h5RFRHbmg4NDlBTW9vNUtBY1E0MmpRYTd0UklnS2Z1OTJDdVNPVDBhbC11TlliaDhHRUdCTmZPOXhLa0VpR04ydEYyWG1EamRJSFZtdWN5MlJLeFZYWERrZkpvNlVLTDdYT255OW1OM2pOTQ?oc=5)

### 미국 2026년 9월 비자 불레틴, 인도 가족 기반 영주권 전진

미국 2026년 9월 비자 불레틴에서 인도 신청자의 가족 기반 영주권 순위가 앞당겨졌다. 가족 초청 영주권 대기 순번이 일부 진전됐다.

**시사점** — 한국 가족초청(F 계열) 신청자도 9월 비자 불레틴에서 자신의 우선일자가 컷오프를 넘었는지 확인해야 한다.

[US September 2026 Visa Bulletin Advances Family-Ba](https://news.google.com/rss/articles/CBMiaEFVX3lxTFBZbTBZSHJhT2d1YWxmWnB3TE1IYkZ1QVgzVnYwbHNpaHhoQ0FrSFNKdmpiYTZydWZXTzlFZkVaYUM1WVpSdVljUE5JRk5VbEdOb1psUUpkOUpIY2YwTkx4c25fai1pbHdI?oc=5)

### 🆕 2026년 8월 미국 비자 불레틴 공개

국제법률·비즈니스서비스그룹(ILBSG)이 2026년 8월 미국 비자 불레틴을 공개했다. 비자 불레틴은 매달 취업 기반·가족 기반 영주권의 우선일자 컷오프를 정한다.

**시사점** — 8월 컷오프와 자신의 우선일자를 대조해야 하는 한국 취업이민(EB-2·EB-3)·가족 이민 신청자가 대상이다.

[August 2026 Visa Bulletin - International Legal an](https://news.google.com/rss/articles/CBMidEFVX3lxTE1tM0RZa1A4X080MmJPMjFqNm1tenhDU3hXckJTSGhaYkcyR1NnRmdJSU5MWWZCV21uQXdkRWEyb3B0SEJkdEEwWGplSF9IR2RveE1kTjkyY3VEN0lGTXU1TFdKRG1sZWdvMHR1SUpRckQ5aG0w?oc=5)

### ‘This is a flawed visa’: Indian-American entrepreneur calls for end of H-1B, seeks new immigration system | Hindustan Times - Hindustan Times

‘This is a flawed visa’: Indian-American entrepreneur calls for end of H-1B, seeks new immigration system | Hindustan Times    Hindustan Times

[‘This is a flawed visa’: Indian-American entrepren](https://news.google.com/rss/articles/CBMi7gFBVV95cUxOalJDRVpFYmtxQWVfLUZZalJVd2FHMUR5YW92eUN4S01uOGs1NVZkUjVOT25GMmFZcThUeDF6ZFc2ZkRSVS1ia3NNTGk3ejRoMGY1NExDUGNrYXUtaTczRS1NTGZTOG5Qakxod1l0WWxVcHVkb2RtNGt5bW9VdTFReEgwSmFSbkdKa3kwNnpIMDVmTFRrVjNSZ0Rub3FVLWRZR2ZmcUtFQlA2b2VYM1luUVM2T0xMNF9nSW15YjZUa3dEYXZLTC00MzBhNmtCYWFNXzdpRTQ0Y2c1ZUZGWE1KZUZXSDZFTUpfeUhmakhn0gHzAUFVX3lxTE1feTlubUxQVmcxV2NVc1VFTWRwQ1FmeHlnVEVPOW5CT2ZtSnVyVF9OcVIzaW05SkI1QnczNXJ3MFo4b2VhQjM2R2h2dW9PcnFIWGhTQWZ2SHAxaUZUTkhJMU1Ba25lRURBNjVVU1VTdTM5aTFTa25ra0Fneks2REhyZk9ZekY4T1VqRnYxTndTV1NpaGV3T3NyODRtQ3RFMm1ZdDV3Qnh1aWlsS1ItNnBSdE1MVlpKQXVSSWFPY24xaEFBQVdNUm9jWWtXQWkxLVgwSnVIUFVHbFBacDdTTWNld2kwX01odHdzS1NfMHptRlNSQQ?oc=5)

## 시장 지표

- KOSPI: 6,913 +0.9%
- 나스닥: 26,180 +0.4%
- 미 10년물: 4.74% +0.9%
- USD/KRW: ₩1,385
