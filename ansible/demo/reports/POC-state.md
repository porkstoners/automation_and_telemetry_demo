
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 491 | 479 | 12 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| cmp308 |  87 | 82 | 5 | Hardware |
| smv462 |  56 | 55 | 1 | Hardware |
| ta366 |  72 | 71 | 1 | Hardware |
| ta367 |  75 | 74 | 1 | Hardware |
| ta368 |  80 | 79 | 1 | Hardware |
| ta373 |  71 | 70 | 1 | Hardware |
| up522 |  50 | 48 | 2 | Hardware, BGP |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| Hardware |  408 | 397 | 11 |
| NTP |  7 | 7 | 0 |
| Interface State |  22 | 22 | 0 |
| LLDP Topology |  22 | 22 | 0 |
| IP Reachability |  18 | 18 | 0 |
| BGP |  7 | 6 | 1 |
| Reload Cause |  7 | 7 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 4 | cmp308 | Hardware | Power supply state | Power supply 5 | FAIL | Power supply state is "powerLoss" |
| 5 | cmp308 | Hardware | Power supply state | Power supply 4 | FAIL | Power supply state is "powerLoss" |
| 6 | cmp308 | Hardware | Power supply state | Power supply 6 | FAIL | Power supply state is "powerLoss" |
| 8 | smv462 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 10 | ta366 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 12 | ta367 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 14 | ta368 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 16 | ta373 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 18 | up522 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 25 | cmp308 | Hardware | fan status (power supplies) | PowerSupply7 | FAIL | fan status is "notInserted" |
| 26 | cmp308 | Hardware | fan status (power supplies) | PowerSupply8 | FAIL | fan status is "notInserted" |
| 484 | up522 | BGP | ArBGP is configured and operating | ArBGP | FAIL | Operating routing protocol model: ribd |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | cmp308 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 2 | cmp308 | Hardware | Power supply state | Power supply 3 | PASS |  |
| 3 | cmp308 | Hardware | Power supply state | Power supply 2 | PASS |  |
| 4 | cmp308 | Hardware | Power supply state | Power supply 5 | FAIL | Power supply state is "powerLoss" |
| 5 | cmp308 | Hardware | Power supply state | Power supply 4 | FAIL | Power supply state is "powerLoss" |
| 6 | cmp308 | Hardware | Power supply state | Power supply 6 | FAIL | Power supply state is "powerLoss" |
| 7 | smv462 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 8 | smv462 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 9 | ta366 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 10 | ta366 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 11 | ta367 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 12 | ta367 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 13 | ta368 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 14 | ta368 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 15 | ta373 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 16 | ta373 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 17 | up522 | Hardware | Power supply state | Power supply 1 | PASS |  |
| 18 | up522 | Hardware | Power supply state | Power supply 2 | FAIL | Power supply state is "powerLoss" |
| 19 | cmp308 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 20 | cmp308 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 21 | cmp308 | Hardware | fan status (power supplies) | PowerSupply3 | PASS |  |
| 22 | cmp308 | Hardware | fan status (power supplies) | PowerSupply4 | PASS |  |
| 23 | cmp308 | Hardware | fan status (power supplies) | PowerSupply5 | PASS |  |
| 24 | cmp308 | Hardware | fan status (power supplies) | PowerSupply6 | PASS |  |
| 25 | cmp308 | Hardware | fan status (power supplies) | PowerSupply7 | FAIL | fan status is "notInserted" |
| 26 | cmp308 | Hardware | fan status (power supplies) | PowerSupply8 | FAIL | fan status is "notInserted" |
| 27 | smv462 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 28 | smv462 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 29 | ta366 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 30 | ta366 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 31 | ta367 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 32 | ta367 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 33 | ta368 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 34 | ta368 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 35 | ta373 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 36 | ta373 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 37 | up522 | Hardware | fan status (power supplies) | PowerSupply1 | PASS |  |
| 38 | up522 | Hardware | fan status (power supplies) | PowerSupply2 | PASS |  |
| 39 | cmp308 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 40 | cmp308 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 41 | cmp308 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 42 | cmp308 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 43 | cmp308 | Hardware | fan status (fan tray) | Tray 5 | PASS |  |
| 44 | cmp308 | Hardware | fan status (fan tray) | Tray 6 | PASS |  |
| 45 | smv462 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 46 | smv462 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 47 | smv462 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 48 | ta366 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 49 | ta366 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 50 | ta366 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 51 | ta366 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 52 | ta367 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 53 | ta367 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 54 | ta367 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 55 | ta367 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 56 | ta368 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 57 | ta368 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 58 | ta368 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 59 | ta368 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 60 | ta373 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 61 | ta373 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 62 | ta373 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 63 | ta373 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 64 | up522 | Hardware | fan status (fan tray) | Tray 1 | PASS |  |
| 65 | up522 | Hardware | fan status (fan tray) | Tray 2 | PASS |  |
| 66 | up522 | Hardware | fan status (fan tray) | Tray 3 | PASS |  |
| 67 | up522 | Hardware | fan status (fan tray) | Tray 4 | PASS |  |
| 68 | cmp308 | Hardware | temperature | system temperature | PASS |  |
| 69 | smv462 | Hardware | temperature | system temperature | PASS |  |
| 70 | ta366 | Hardware | temperature | system temperature | PASS |  |
| 71 | ta367 | Hardware | temperature | system temperature | PASS |  |
| 72 | ta368 | Hardware | temperature | system temperature | PASS |  |
| 73 | ta373 | Hardware | temperature | system temperature | PASS |  |
| 74 | up522 | Hardware | temperature | system temperature | PASS |  |
| 75 | cmp308 | Hardware | transceivers manufacturers | port 3/37 | PASS |  |
| 76 | cmp308 | Hardware | transceivers manufacturers | port 3/36 | PASS |  |
| 77 | cmp308 | Hardware | transceivers manufacturers | port 3/35 | PASS |  |
| 78 | cmp308 | Hardware | transceivers manufacturers | port 3/34 | PASS |  |
| 79 | cmp308 | Hardware | transceivers manufacturers | port 3/19 | PASS |  |
| 80 | cmp308 | Hardware | transceivers manufacturers | port 3/18 | PASS |  |
| 81 | cmp308 | Hardware | transceivers manufacturers | port 3/31 | PASS |  |
| 82 | cmp308 | Hardware | transceivers manufacturers | port 3/30 | PASS |  |
| 83 | cmp308 | Hardware | transceivers manufacturers | port 3/15 | PASS |  |
| 84 | cmp308 | Hardware | transceivers manufacturers | port 3/14 | PASS |  |
| 85 | cmp308 | Hardware | transceivers manufacturers | port 3/17 | PASS |  |
| 86 | cmp308 | Hardware | transceivers manufacturers | port 3/16 | PASS |  |
| 87 | cmp308 | Hardware | transceivers manufacturers | port 3/11 | PASS |  |
| 88 | cmp308 | Hardware | transceivers manufacturers | port 3/10 | PASS |  |
| 89 | cmp308 | Hardware | transceivers manufacturers | port 3/13 | PASS |  |
| 90 | cmp308 | Hardware | transceivers manufacturers | port 3/12 | PASS |  |
| 91 | cmp308 | Hardware | transceivers manufacturers | port 3/33 | PASS |  |
| 92 | cmp308 | Hardware | transceivers manufacturers | port 3/32 | PASS |  |
| 93 | cmp308 | Hardware | transceivers manufacturers | port 3/46 | PASS |  |
| 94 | cmp308 | Hardware | transceivers manufacturers | port 3/47 | PASS |  |
| 95 | cmp308 | Hardware | transceivers manufacturers | port 3/44 | PASS |  |
| 96 | cmp308 | Hardware | transceivers manufacturers | port 3/45 | PASS |  |
| 97 | cmp308 | Hardware | transceivers manufacturers | port 3/42 | PASS |  |
| 98 | cmp308 | Hardware | transceivers manufacturers | port 3/43 | PASS |  |
| 99 | cmp308 | Hardware | transceivers manufacturers | port 3/40 | PASS |  |
| 100 | cmp308 | Hardware | transceivers manufacturers | port 3/41 | PASS |  |
| 101 | cmp308 | Hardware | transceivers manufacturers | port 3/48 | PASS |  |
| 102 | cmp308 | Hardware | transceivers manufacturers | port 3/24 | PASS |  |
| 103 | cmp308 | Hardware | transceivers manufacturers | port 3/25 | PASS |  |
| 104 | cmp308 | Hardware | transceivers manufacturers | port 3/26 | PASS |  |
| 105 | cmp308 | Hardware | transceivers manufacturers | port 3/27 | PASS |  |
| 106 | cmp308 | Hardware | transceivers manufacturers | port 3/20 | PASS |  |
| 107 | cmp308 | Hardware | transceivers manufacturers | port 3/21 | PASS |  |
| 108 | cmp308 | Hardware | transceivers manufacturers | port 3/22 | PASS |  |
| 109 | cmp308 | Hardware | transceivers manufacturers | port 3/23 | PASS |  |
| 110 | cmp308 | Hardware | transceivers manufacturers | port 3/28 | PASS |  |
| 111 | cmp308 | Hardware | transceivers manufacturers | port 3/29 | PASS |  |
| 112 | cmp308 | Hardware | transceivers manufacturers | port 3/1 | PASS |  |
| 113 | cmp308 | Hardware | transceivers manufacturers | port 3/3 | PASS |  |
| 114 | cmp308 | Hardware | transceivers manufacturers | port 3/2 | PASS |  |
| 115 | cmp308 | Hardware | transceivers manufacturers | port 3/5 | PASS |  |
| 116 | cmp308 | Hardware | transceivers manufacturers | port 3/39 | PASS |  |
| 117 | cmp308 | Hardware | transceivers manufacturers | port 3/7 | PASS |  |
| 118 | cmp308 | Hardware | transceivers manufacturers | port 3/6 | PASS |  |
| 119 | cmp308 | Hardware | transceivers manufacturers | port 3/9 | PASS |  |
| 120 | cmp308 | Hardware | transceivers manufacturers | port 3/8 | PASS |  |
| 121 | cmp308 | Hardware | transceivers manufacturers | port 3/38 | PASS |  |
| 122 | cmp308 | Hardware | transceivers manufacturers | port 3/4 | PASS |  |
| 123 | smv462 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 124 | smv462 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 125 | smv462 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 126 | smv462 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 127 | smv462 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 128 | smv462 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 129 | smv462 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 130 | smv462 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 131 | smv462 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 132 | smv462 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 133 | smv462 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 134 | smv462 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 135 | smv462 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 136 | smv462 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 137 | smv462 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 138 | smv462 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 139 | smv462 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 140 | smv462 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 141 | smv462 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 142 | smv462 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 143 | smv462 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 144 | smv462 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 145 | smv462 | Hardware | transceivers manufacturers | port 36 | PASS |  |
| 146 | smv462 | Hardware | transceivers manufacturers | port 35 | PASS |  |
| 147 | smv462 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 148 | smv462 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 149 | smv462 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 150 | smv462 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 151 | smv462 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 152 | smv462 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 153 | smv462 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 154 | smv462 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 155 | smv462 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 156 | smv462 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 157 | smv462 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 158 | smv462 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 159 | ta366 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 160 | ta366 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 161 | ta366 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 162 | ta366 | Hardware | transceivers manufacturers | port 35 | PASS |  |
| 163 | ta366 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 164 | ta366 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 165 | ta366 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 166 | ta366 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 167 | ta366 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 168 | ta366 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 169 | ta366 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 170 | ta366 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 171 | ta366 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 172 | ta366 | Hardware | transceivers manufacturers | port 46 | PASS |  |
| 173 | ta366 | Hardware | transceivers manufacturers | port 47 | PASS |  |
| 174 | ta366 | Hardware | transceivers manufacturers | port 44 | PASS |  |
| 175 | ta366 | Hardware | transceivers manufacturers | port 45 | PASS |  |
| 176 | ta366 | Hardware | transceivers manufacturers | port 42 | PASS |  |
| 177 | ta366 | Hardware | transceivers manufacturers | port 43 | PASS |  |
| 178 | ta366 | Hardware | transceivers manufacturers | port 40 | PASS |  |
| 179 | ta366 | Hardware | transceivers manufacturers | port 41 | PASS |  |
| 180 | ta366 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 181 | ta366 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 182 | ta366 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 183 | ta366 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 184 | ta366 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 185 | ta366 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 186 | ta366 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 187 | ta366 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 188 | ta366 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 189 | ta366 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 190 | ta366 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 191 | ta366 | Hardware | transceivers manufacturers | port 38 | PASS |  |
| 192 | ta366 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 193 | ta366 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 194 | ta366 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 195 | ta366 | Hardware | transceivers manufacturers | port 39 | PASS |  |
| 196 | ta366 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 197 | ta366 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 198 | ta366 | Hardware | transceivers manufacturers | port 48 | PASS |  |
| 199 | ta366 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 200 | ta366 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 201 | ta366 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 202 | ta366 | Hardware | transceivers manufacturers | port 54 | PASS |  |
| 203 | ta366 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 204 | ta366 | Hardware | transceivers manufacturers | port 49 | PASS |  |
| 205 | ta366 | Hardware | transceivers manufacturers | port 51 | PASS |  |
| 206 | ta366 | Hardware | transceivers manufacturers | port 36 | PASS |  |
| 207 | ta366 | Hardware | transceivers manufacturers | port 53 | PASS |  |
| 208 | ta366 | Hardware | transceivers manufacturers | port 52 | PASS |  |
| 209 | ta366 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 210 | ta366 | Hardware | transceivers manufacturers | port 37 | PASS |  |
| 211 | ta366 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 212 | ta366 | Hardware | transceivers manufacturers | port 50 | PASS |  |
| 213 | ta367 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 214 | ta367 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 215 | ta367 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 216 | ta367 | Hardware | transceivers manufacturers | port 35 | PASS |  |
| 217 | ta367 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 218 | ta367 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 219 | ta367 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 220 | ta367 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 221 | ta367 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 222 | ta367 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 223 | ta367 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 224 | ta367 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 225 | ta367 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 226 | ta367 | Hardware | transceivers manufacturers | port 46 | PASS |  |
| 227 | ta367 | Hardware | transceivers manufacturers | port 47 | PASS |  |
| 228 | ta367 | Hardware | transceivers manufacturers | port 44 | PASS |  |
| 229 | ta367 | Hardware | transceivers manufacturers | port 45 | PASS |  |
| 230 | ta367 | Hardware | transceivers manufacturers | port 42 | PASS |  |
| 231 | ta367 | Hardware | transceivers manufacturers | port 43 | PASS |  |
| 232 | ta367 | Hardware | transceivers manufacturers | port 40 | PASS |  |
| 233 | ta367 | Hardware | transceivers manufacturers | port 41 | PASS |  |
| 234 | ta367 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 235 | ta367 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 236 | ta367 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 237 | ta367 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 238 | ta367 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 239 | ta367 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 240 | ta367 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 241 | ta367 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 242 | ta367 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 243 | ta367 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 244 | ta367 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 245 | ta367 | Hardware | transceivers manufacturers | port 38 | PASS |  |
| 246 | ta367 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 247 | ta367 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 248 | ta367 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 249 | ta367 | Hardware | transceivers manufacturers | port 39 | PASS |  |
| 250 | ta367 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 251 | ta367 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 252 | ta367 | Hardware | transceivers manufacturers | port 48 | PASS |  |
| 253 | ta367 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 254 | ta367 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 255 | ta367 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 256 | ta367 | Hardware | transceivers manufacturers | port 54 | PASS |  |
| 257 | ta367 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 258 | ta367 | Hardware | transceivers manufacturers | port 49 | PASS |  |
| 259 | ta367 | Hardware | transceivers manufacturers | port 51 | PASS |  |
| 260 | ta367 | Hardware | transceivers manufacturers | port 36 | PASS |  |
| 261 | ta367 | Hardware | transceivers manufacturers | port 53 | PASS |  |
| 262 | ta367 | Hardware | transceivers manufacturers | port 52 | PASS |  |
| 263 | ta367 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 264 | ta367 | Hardware | transceivers manufacturers | port 37 | PASS |  |
| 265 | ta367 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 266 | ta367 | Hardware | transceivers manufacturers | port 50 | PASS |  |
| 267 | ta368 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 268 | ta368 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 269 | ta368 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 270 | ta368 | Hardware | transceivers manufacturers | port 35 | PASS |  |
| 271 | ta368 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 272 | ta368 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 273 | ta368 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 274 | ta368 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 275 | ta368 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 276 | ta368 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 277 | ta368 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 278 | ta368 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 279 | ta368 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 280 | ta368 | Hardware | transceivers manufacturers | port 46 | PASS |  |
| 281 | ta368 | Hardware | transceivers manufacturers | port 47 | PASS |  |
| 282 | ta368 | Hardware | transceivers manufacturers | port 44 | PASS |  |
| 283 | ta368 | Hardware | transceivers manufacturers | port 45 | PASS |  |
| 284 | ta368 | Hardware | transceivers manufacturers | port 42 | PASS |  |
| 285 | ta368 | Hardware | transceivers manufacturers | port 43 | PASS |  |
| 286 | ta368 | Hardware | transceivers manufacturers | port 40 | PASS |  |
| 287 | ta368 | Hardware | transceivers manufacturers | port 41 | PASS |  |
| 288 | ta368 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 289 | ta368 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 290 | ta368 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 291 | ta368 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 292 | ta368 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 293 | ta368 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 294 | ta368 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 295 | ta368 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 296 | ta368 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 297 | ta368 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 298 | ta368 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 299 | ta368 | Hardware | transceivers manufacturers | port 38 | PASS |  |
| 300 | ta368 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 301 | ta368 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 302 | ta368 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 303 | ta368 | Hardware | transceivers manufacturers | port 39 | PASS |  |
| 304 | ta368 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 305 | ta368 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 306 | ta368 | Hardware | transceivers manufacturers | port 48 | PASS |  |
| 307 | ta368 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 308 | ta368 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 309 | ta368 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 310 | ta368 | Hardware | transceivers manufacturers | port 54 | PASS |  |
| 311 | ta368 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 312 | ta368 | Hardware | transceivers manufacturers | port 49 | PASS |  |
| 313 | ta368 | Hardware | transceivers manufacturers | port 51 | PASS |  |
| 314 | ta368 | Hardware | transceivers manufacturers | port 36 | PASS |  |
| 315 | ta368 | Hardware | transceivers manufacturers | port 53 | PASS |  |
| 316 | ta368 | Hardware | transceivers manufacturers | port 52 | PASS |  |
| 317 | ta368 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 318 | ta368 | Hardware | transceivers manufacturers | port 37 | PASS |  |
| 319 | ta368 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 320 | ta368 | Hardware | transceivers manufacturers | port 50 | PASS |  |
| 321 | ta373 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 322 | ta373 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 323 | ta373 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 324 | ta373 | Hardware | transceivers manufacturers | port 35 | PASS |  |
| 325 | ta373 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 326 | ta373 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 327 | ta373 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 328 | ta373 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 329 | ta373 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 330 | ta373 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 331 | ta373 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 332 | ta373 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 333 | ta373 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 334 | ta373 | Hardware | transceivers manufacturers | port 46 | PASS |  |
| 335 | ta373 | Hardware | transceivers manufacturers | port 47 | PASS |  |
| 336 | ta373 | Hardware | transceivers manufacturers | port 44 | PASS |  |
| 337 | ta373 | Hardware | transceivers manufacturers | port 45 | PASS |  |
| 338 | ta373 | Hardware | transceivers manufacturers | port 42 | PASS |  |
| 339 | ta373 | Hardware | transceivers manufacturers | port 43 | PASS |  |
| 340 | ta373 | Hardware | transceivers manufacturers | port 40 | PASS |  |
| 341 | ta373 | Hardware | transceivers manufacturers | port 41 | PASS |  |
| 342 | ta373 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 343 | ta373 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 344 | ta373 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 345 | ta373 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 346 | ta373 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 347 | ta373 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 348 | ta373 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 349 | ta373 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 350 | ta373 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 351 | ta373 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 352 | ta373 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 353 | ta373 | Hardware | transceivers manufacturers | port 38 | PASS |  |
| 354 | ta373 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 355 | ta373 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 356 | ta373 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 357 | ta373 | Hardware | transceivers manufacturers | port 39 | PASS |  |
| 358 | ta373 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 359 | ta373 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 360 | ta373 | Hardware | transceivers manufacturers | port 48 | PASS |  |
| 361 | ta373 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 362 | ta373 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 363 | ta373 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 364 | ta373 | Hardware | transceivers manufacturers | port 54 | PASS |  |
| 365 | ta373 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 366 | ta373 | Hardware | transceivers manufacturers | port 49 | PASS |  |
| 367 | ta373 | Hardware | transceivers manufacturers | port 51 | PASS |  |
| 368 | ta373 | Hardware | transceivers manufacturers | port 36 | PASS |  |
| 369 | ta373 | Hardware | transceivers manufacturers | port 53 | PASS |  |
| 370 | ta373 | Hardware | transceivers manufacturers | port 52 | PASS |  |
| 371 | ta373 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 372 | ta373 | Hardware | transceivers manufacturers | port 37 | PASS |  |
| 373 | ta373 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 374 | ta373 | Hardware | transceivers manufacturers | port 50 | PASS |  |
| 375 | up522 | Hardware | transceivers manufacturers | port 11 | PASS |  |
| 376 | up522 | Hardware | transceivers manufacturers | port 10 | PASS |  |
| 377 | up522 | Hardware | transceivers manufacturers | port 6 | PASS |  |
| 378 | up522 | Hardware | transceivers manufacturers | port 13 | PASS |  |
| 379 | up522 | Hardware | transceivers manufacturers | port 12 | PASS |  |
| 380 | up522 | Hardware | transceivers manufacturers | port 17 | PASS |  |
| 381 | up522 | Hardware | transceivers manufacturers | port 15 | PASS |  |
| 382 | up522 | Hardware | transceivers manufacturers | port 23 | PASS |  |
| 383 | up522 | Hardware | transceivers manufacturers | port 24 | PASS |  |
| 384 | up522 | Hardware | transceivers manufacturers | port 25 | PASS |  |
| 385 | up522 | Hardware | transceivers manufacturers | port 26 | PASS |  |
| 386 | up522 | Hardware | transceivers manufacturers | port 27 | PASS |  |
| 387 | up522 | Hardware | transceivers manufacturers | port 20 | PASS |  |
| 388 | up522 | Hardware | transceivers manufacturers | port 21 | PASS |  |
| 389 | up522 | Hardware | transceivers manufacturers | port 22 | PASS |  |
| 390 | up522 | Hardware | transceivers manufacturers | port 16 | PASS |  |
| 391 | up522 | Hardware | transceivers manufacturers | port 19 | PASS |  |
| 392 | up522 | Hardware | transceivers manufacturers | port 32 | PASS |  |
| 393 | up522 | Hardware | transceivers manufacturers | port 31 | PASS |  |
| 394 | up522 | Hardware | transceivers manufacturers | port 30 | PASS |  |
| 395 | up522 | Hardware | transceivers manufacturers | port 28 | PASS |  |
| 396 | up522 | Hardware | transceivers manufacturers | port 29 | PASS |  |
| 397 | up522 | Hardware | transceivers manufacturers | port 34 | PASS |  |
| 398 | up522 | Hardware | transceivers manufacturers | port 1 | PASS |  |
| 399 | up522 | Hardware | transceivers manufacturers | port 33 | PASS |  |
| 400 | up522 | Hardware | transceivers manufacturers | port 3 | PASS |  |
| 401 | up522 | Hardware | transceivers manufacturers | port 2 | PASS |  |
| 402 | up522 | Hardware | transceivers manufacturers | port 5 | PASS |  |
| 403 | up522 | Hardware | transceivers manufacturers | port 4 | PASS |  |
| 404 | up522 | Hardware | transceivers manufacturers | port 7 | PASS |  |
| 405 | up522 | Hardware | transceivers manufacturers | port 18 | PASS |  |
| 406 | up522 | Hardware | transceivers manufacturers | port 9 | PASS |  |
| 407 | up522 | Hardware | transceivers manufacturers | port 8 | PASS |  |
| 408 | up522 | Hardware | transceivers manufacturers | port 14 | PASS |  |
| 409 | cmp308 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 410 | smv462 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 411 | ta366 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 412 | ta367 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 413 | ta368 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 414 | ta373 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 415 | up522 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 416 | cmp308 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/1/1 | PASS |  |
| 417 | cmp308 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/2/1 | PASS |  |
| 418 | cmp308 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/3/1 | PASS |  |
| 419 | cmp308 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/4/1 | PASS |  |
| 420 | cmp308 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/5/1 | PASS |  |
| 421 | smv462 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1/1 | PASS |  |
| 422 | smv462 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 | PASS |  |
| 423 | smv462 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/1 | PASS |  |
| 424 | ta366 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet49/1 | PASS |  |
| 425 | ta366 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 | PASS |  |
| 426 | ta367 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet49/1 | PASS |  |
| 427 | ta367 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 | PASS |  |
| 428 | ta367 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet51/1 | PASS |  |
| 429 | ta368 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 | PASS |  |
| 430 | ta368 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet49/1 | PASS |  |
| 431 | ta368 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 | PASS |  |
| 432 | ta368 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet51/1 | PASS |  |
| 433 | ta368 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet52/1 | PASS |  |
| 434 | ta373 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 | PASS |  |
| 435 | ta373 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet50/1 | PASS |  |
| 436 | up522 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2/1 | PASS |  |
| 437 | up522 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3/1 | PASS |  |
| 438 | cmp308 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/1/1 - remote: smv462_Ethernet1/1 | PASS |  |
| 439 | cmp308 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/2/1 - remote: ta366_Ethernet49/1 | PASS |  |
| 440 | cmp308 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/3/1 - remote: ta367_Ethernet50/1 | PASS |  |
| 441 | cmp308 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/4/1 - remote: ta368_Ethernet51/1 | PASS |  |
| 442 | cmp308 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/5/1 - remote: ta373_Ethernet50/1 | PASS |  |
| 443 | smv462 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1/1 - remote: cmp308_Ethernet3/1/1 | PASS |  |
| 444 | smv462 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: ta367_Ethernet49/1 | PASS |  |
| 445 | smv462 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/1 - remote: ta368_Ethernet50/1 | PASS |  |
| 446 | ta366 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet49/1 - remote: cmp308_Ethernet3/2/1 | PASS |  |
| 447 | ta366 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: ta368_Ethernet52/1 | PASS |  |
| 448 | ta367 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet49/1 - remote: smv462_Ethernet2/1 | PASS |  |
| 449 | ta367 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: cmp308_Ethernet3/3/1 | PASS |  |
| 450 | ta367 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet51/1 - remote: ta368_Ethernet49/1 | PASS |  |
| 451 | ta368 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: up522_Ethernet2/1 | PASS |  |
| 452 | ta368 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet49/1 - remote: ta367_Ethernet51/1 | PASS |  |
| 453 | ta368 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: smv462_Ethernet3/1 | PASS |  |
| 454 | ta368 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet51/1 - remote: cmp308_Ethernet3/4/1 | PASS |  |
| 455 | ta368 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet52/1 - remote: ta366_Ethernet50/1 | PASS |  |
| 456 | ta373 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: up522_Ethernet3/1 | PASS |  |
| 457 | ta373 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet50/1 - remote: cmp308_Ethernet3/5/1 | PASS |  |
| 458 | up522 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2/1 - remote: ta368_Ethernet2 | PASS |  |
| 459 | up522 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3/1 - remote: ta373_Ethernet2 | PASS |  |
| 460 | cmp308 | IP Reachability | ip reachability test p2p links | Source: cmp308_Ethernet3/1/1 - Destination: smv462_Ethernet1/1 | PASS |  |
| 461 | cmp308 | IP Reachability | ip reachability test p2p links | Source: cmp308_Ethernet3/2/1 - Destination: ta366_Ethernet49/1 | PASS |  |
| 462 | cmp308 | IP Reachability | ip reachability test p2p links | Source: cmp308_Ethernet3/3/1 - Destination: ta367_Ethernet50/1 | PASS |  |
| 463 | cmp308 | IP Reachability | ip reachability test p2p links | Source: cmp308_Ethernet3/4/1 - Destination: ta368_Ethernet51/1 | PASS |  |
| 464 | cmp308 | IP Reachability | ip reachability test p2p links | Source: cmp308_Ethernet3/5/1 - Destination: ta373_Ethernet50/1 | PASS |  |
| 465 | smv462 | IP Reachability | ip reachability test p2p links | Source: smv462_Ethernet1/1 - Destination: cmp308_Ethernet3/1/1 | PASS |  |
| 466 | smv462 | IP Reachability | ip reachability test p2p links | Source: smv462_Ethernet2/1 - Destination: ta367_Ethernet49/1 | PASS |  |
| 467 | smv462 | IP Reachability | ip reachability test p2p links | Source: smv462_Ethernet3/1 - Destination: ta368_Ethernet50/1 | PASS |  |
| 468 | ta366 | IP Reachability | ip reachability test p2p links | Source: ta366_Ethernet49/1 - Destination: cmp308_Ethernet3/2/1 | PASS |  |
| 469 | ta366 | IP Reachability | ip reachability test p2p links | Source: ta366_Ethernet50/1 - Destination: ta368_Ethernet52/1 | PASS |  |
| 470 | ta367 | IP Reachability | ip reachability test p2p links | Source: ta367_Ethernet49/1 - Destination: smv462_Ethernet2/1 | PASS |  |
| 471 | ta367 | IP Reachability | ip reachability test p2p links | Source: ta367_Ethernet50/1 - Destination: cmp308_Ethernet3/3/1 | PASS |  |
| 472 | ta367 | IP Reachability | ip reachability test p2p links | Source: ta367_Ethernet51/1 - Destination: ta368_Ethernet49/1 | PASS |  |
| 473 | ta368 | IP Reachability | ip reachability test p2p links | Source: ta368_Ethernet49/1 - Destination: ta367_Ethernet51/1 | PASS |  |
| 474 | ta368 | IP Reachability | ip reachability test p2p links | Source: ta368_Ethernet50/1 - Destination: smv462_Ethernet3/1 | PASS |  |
| 475 | ta368 | IP Reachability | ip reachability test p2p links | Source: ta368_Ethernet51/1 - Destination: cmp308_Ethernet3/4/1 | PASS |  |
| 476 | ta368 | IP Reachability | ip reachability test p2p links | Source: ta368_Ethernet52/1 - Destination: ta366_Ethernet50/1 | PASS |  |
| 477 | ta373 | IP Reachability | ip reachability test p2p links | Source: ta373_Ethernet50/1 - Destination: cmp308_Ethernet3/5/1 | PASS |  |
| 478 | cmp308 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 479 | smv462 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 480 | ta366 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 481 | ta367 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 482 | ta368 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 483 | ta373 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 484 | up522 | BGP | ArBGP is configured and operating | ArBGP | FAIL | Operating routing protocol model: ribd |
| 485 | cmp308 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 486 | smv462 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 487 | ta366 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 488 | ta367 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 489 | ta368 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 490 | ta373 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |
| 491 | up522 | Reload Cause | Reload Cause: Reload requested by the user | Reload Cause | PASS |  |