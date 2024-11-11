Setup = {
    ['PC-er'] = false,
    ['Team'] = 'Pirates',
    ['Auto Team'] = false,
        ['Enabled'] = false,
        ['Lock'] = {
            ['Pirate'] = {0, 30000000},
            ['Marines'] = {0, 30000000}
        }
    },
    ['Panic % Health'] = {20, 55},
    ['Chatting'] = {},
    ['Lock Cam'] = false,
    ['Hop Region'] = 'Singapore',
    ['Random Y Tween'] = false,
    ['Click Delay'] = 0.1
}
Hunter = {
    ['Ignore'] = {
        ['Fruit'] = {
            'Meme-Meme'
        },
        ['Timer'] = 72,
        ['V4'] = true
    },
    ['Gun Mode'] = true,
    ['Predict Move'] = true,
    ['Hit And Run'] = true,
    ['Random Position'] = true
}
Booster = {
    ['Hide Gui'] = false,
    ['Showcase Mode'] = false,
    ['White Screen'] = false,
    ['Hide Map'] = false
}
Skills = {
    ['Melee'] = {
        ['Enabled'] = {true, true},
        ['Z'] = {true, 0.1, 0.165},
        ['X'] = {true, 0.3, 0.246},
        ['C'] = {true, 0.5, 0.125}
    },
    ['Blox Fruit'] = {
        ['Enabled'] = {true, true},
        ['Z'] = {true, 1.325, 0.9},
        ['X'] = {true, 0.6, 0.235},
        ['C'] = {true, 0.2, 0.435},
        ['V'] = {true, 0.3, 0.195},
        ['F'] = {true, 0, 0.6}
    },
    ['Sword'] = {
        ['Enabled'] = {true, true},
        ['Z'] = {true, 0.5, 0.2},
        ['X'] = {true, 0.3, 0.4},
    },
    ['Gun'] = {
        ['Enabled'] = {false, false},
        ['Z'] = {true, 0.5, 0.2},
        ['X'] = {true, 0.3, 0.4},
    }
}
Macro = {
    ['Enabled'] = true,
    ['Skills'] = true,
        [1] = {'Melee', {'C', 'Z'}},
        [2] = {'Blox Fruit', {'F','C'}},
        [3] = {'Sword', {'X', 'Z'}},
        [4] = {'Melee', {'X'}},
        [5] = {'Gun', {'Z', 'V'}},
        [6] = {'Blox Fruit', {'Z', 'F'}}
    }
}
Counter = {
    ['Enabled'] = true,
    ['Webhook'] = {
        ['Enabled'] = false,
        ['Url'] = ''
    },
    ['Theme'] = {
        ['Character'] = 'Yae',
        ['Custom'] = {
            ['Enabled'] = false,
            ['Config'] = {
                ['Background'] = '',
                ['Character'] = '',
                ['Icon'] = '',
                ['Button Image'] = '',
                ['Color'] = {
                    ['Text'] = Color3.fromRGB(255, 255, 255),
                    ['Stroke'] = Color3.fromRGB(255, 255, 255)
                }
            }
        }
    },
}
