# Sequence Intro

## There will be time for questions

البته plantuml خیلی امکانات زیادی داره
الآن هدف اینه که یه آشنایی کلی داشته باشیم از این‌که:

کشیدن نمودارها
آشنایی کلی با اینکه چه امکاناتی می‌تونه بهمون بده

یک لیستی از امکانات پرکاربرد آماده کردم. یکی یکی با هم مرور می‌کنیم

- simple arrow (->)
- dotted arrow( -->)
- self link
- link message (:)
- new line (\n)
- outside arrow (-> / ?)
- note (note right:)
- note multiline (end note)
- note place (left of) (over)
- activate and deactivate (activate/deactivate/destroy)

-Any Question?

- group (group label/end)
- defining orders & shapes (actor) 
- long title ("" & as)
- color (actor user #red)
- autonumber

## sample:

@startuml test

user->service:Get service
service->database:DB Query
database->service

@enduml
