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
      <td>Ex: <code>sm_ban Shane wallhax</code></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Vote Crits</strong><br />(Random Crits)</td>
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

Example, entering `/map badwater` will default to `pl_badwater`.

### ❌ `harvest`

> => `koth_harvest_event`

Alphabetically, the Harvest Halloween map comes first:

1. **`koth_harvest_event`** (Halloween)
1. **`koth_harvest_final`**

### ❌ `badlands`

> => `arena_badlands`

Alphabetical order of `badlands` is:

1. **`arena_badlands`**
1. **`cp_badlands`**
1. **`koth_badlands`**
