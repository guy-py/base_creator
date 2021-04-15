base = []
base_length = int(input('base'))
for i in range(base_length):
    base.append(i)
def get_now(unk):
    while str(unk)[0] == '0':
        unk = str(unk)[1:]
    ap = []
    for i in str(unk):
        ap.append(i)
    app = []
    fr = int(str(base_length)[0])
    for i in ap:
        app.append(fr*int(i))
        fr = fr * 2
    srt = 0
    for i in app:
        srt = srt + i
    return int(srt)
while True:
    print(get_now(input()))
