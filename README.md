 r = api.request('search/tweets', {'q':'giraffe'})
            for item in r:
              print(item['text'])
