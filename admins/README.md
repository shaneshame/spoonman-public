# Admin Commands

The chat command `/admin` opens an Admin menu, but it's clunky to use. Everything in the menus can instead be used directly.

<table>
  <thead>
    <tr>
      <th>Command</th>
      <th>Chat</th>
      <th>Console</th>
      <th>Categories</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><strong>Ban Player</strong></td>
      <td><code>/ban &lt;@name|steamid&gt; [minutes|0] &lt;reason&gt;</code></td>
      <td><code>sm_ban &lt;name|steamid&gt; ...</code></td>
      <td>Control</td>
    </tr>
    <tr>
      <td>Ex: <code>/ban @Shane wallhax</code></td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td><strong>Vote Crits</strong> (Random Crits)</td>
      <td><code>/votecrits</code></td>
      <td><code>sm_votecrits</code></td>
      <td>Vote, Cvar</td>
    </tr>
    <tr>
      <td><strong>Vote Scramble</strong></td>
      <td><code>/votescramble</code></td>
      <td><code>sm_votescramble</code></td>
      <td>Vote</td>
    </tr>
    <tr>
      <td><strong>Set Next Map</strong></td>
      <td><code>/setnextmap lakesize_final</code></td>
      <td><code>sm_setnextmap ...</code></td>
      <td>Control, Map</td>
    </tr>
    <tr>
      <td><strong>Change Map</strong></td>
      <td><code>/map lakesize_final</code></td>
      <td><code>sm_map ...</code></td>
      <td>Control, Map</td>
    </tr>
    <tr>
      <td><strong>Vote Ad Lib</strong></td>
      <td><code>/map question-one-word yes no maybe</code></td>
      <td><code>sm_vote "Switch map" Yes "I don't care"</code></td>
      <td>Vote</td>
    </tr>
    <tr>
      <td><strong>Admin Menu</strong></td>
      <td><code>/admin</code></td>
      <td><code>sm_admin</code></td>
      <td>Clunky</td>
    </tr>
  </tbody>
</table>

# Tips

## Shorthand Map Names

If you don't type out the entire map name, the game will choose the closest alphabetical match.

### ✔️ No other matches

```go
/map badwater
// => pl_badwater
```

The only other `badwater` match I have is `pl_badwater_pro`.

### ❌ Multiple Matches Shorthand

```go
/map harvest
// => koth_harvest_event
```

I have two matches for `harvest`.

1. **`koth_harvest_event`** (Halloween)
1. **`koth_harvest_final`**

### ❌ More Examples

```go
/map badlands
// => arena_badlands
```

This will choose **`arena_badlands`**, because the alphabetical order is:

1. **`arena_badlands`**
1. **`cp_badlands`**
1. **`koth_badlands`**
