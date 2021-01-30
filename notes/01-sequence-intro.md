# Sequence Intro

## There will be time for questions

البته plantuml خیلی امکانات زیادی داره
الآن هدف اینه که یه آشنایی کلی داشته باشیم از این‌که:

کشیدن نمودارها
آشنایی کلی با اینکه چه امکاناتی می‌تونه بهمون بده

- simple arrow (->)
- dotted arrow( -->)
- self link
- link message (:)
- new line (\n)
- activate and deactivate (activate/deactivate/destroy)
- outside arrow (-> / ?)
- note (note right:)
- note multiline (end note)
- note place (left of) (over)

-Any Question?

- group (group label/end)
- defining shapes (actor) (ordered)
- long title ("" & as)

## sample:

@startuml test

user->service:Get service
service->database:DB Query
database->service

@enduml
