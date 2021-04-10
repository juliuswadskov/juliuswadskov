## JavaScript
```js
const name = `raag2005`
const discord = `raag2005#0001`
const twitch = `https://www.twitch.tv/raag2005_`

const websites = ['raag2005.dk']

console.log(`Hello i am ${name}`)
console.log(`my twitch is ${twitch}`)
console.log(`and i own the websites below:`)
for (const key in websites) {
  console.log(` - ${websites[key]}`)
}
```

## Lua
```lua
local name = 'raag2005'
local discord = 'raag2005#0001'
local twitch = 'https://www.twitch.tv/raag2005_'

local websites = {'raag2005.dk', 'raagart.com}

print('Hello i am ' .. name)
print('my twitch is ' .. twitch)
print('and i own the websites below:')
for k, v in pairs(websites) do
  print(' - ' .. v)
end
```

## Output
```
Hello i am raag2005
my twitch is https://www.twitch.tv/raag2005_
and i own the websites below:
 - raag2005.dk
```
