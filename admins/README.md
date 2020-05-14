# Admin Commands

The chat command `/admin` opens an Admin menu, but it's clunky to use. Everything in the menus can instead be used directly.

<table>
  <thead>
    <tr>
      <th>Command</th>
      <th>Name</th>
      <th>Chat</th>
      <th>Console</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><strong><code>sm_ban</code></strong></td>
      <td rowspan="2">Ban Player</td>
      <td><code>/ban &lt;@name|steamid&gt; [minutes|0] &lt;reason&gt;</code></td>
      <td><code>sm_ban &lt;name|steamid&gt; [minutes|0] &lt;reason&gt;</code></td>
    </tr>
    <tr>
      <td>Ex: <code>/ban @Shane wallhax</code></td>
      <td>Ex: <code>sm_ban Shane wallhax</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_votecrits</code></strong></td>
      <td>
        Random Crits
      </td>
      <td><code>/votecrits</code></td>
      <td><code>sm_votecrits</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_votescramble</code></strong></td>
      <td>Scramble Teams</td>
      <td><code>/votescramble</code></td>
      <td><code>sm_votescramble</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_setnextmap</code></strong></td>
      <td>
          Set Next Map
          <sup><a href="#-shorthand-map-names">[1]</a></sup>
      </td>
      <td><code>/setnextmap lakeside_final</code></td>
      <td><code>sm_setnextmap lakeside_final</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_map</code></strong></td>
      <td>
          Change Map
          <sup><a href="#-shorthand-map-names">[1]</a></sup>
      </td>
      <td><code>/map lakeside_final</code></td>
      <td><code>sm_map lakeside_final</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_votealltalk</code></strong></td>
      <td>All Talk</td>
      <td><code>/votealltalk</code></td>
      <td><code>sm_votealltalk</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_vote</code></strong></td>
      <td>
        Ad Lib Vote<br />
        (Vote about anything)
      </td>
      <td><code>/map question-one-word yes no maybe</code></td>
      <td><code>sm_vote "Switch map" Yes "I don't care"</code></td>
    </tr>
    <tr>
      <td><strong><code>sm_admin</code></strong></td>
      <td>Admin Menu</td>
      <td><code>/admin</code></td>
      <td><code>sm_admin</code></td>
    </tr>
  </tbody>
</table>

# Risky Business

<img src="https://hollywoodsuite.ca/wp-content/uploads/poster/HS900369_poster_1920_1080.jpg" height="40%" width="40%" />

## 🚧 Shorthand Map Names

Game will choose the closest alphabetical match.

### Example: **`/map badlands` ➡️ `arena_badlands`**

Instead, use the full map name: **`/map cp_badlands`**

### ⚠️ `badlands`

Alphabetical order of **`badlands`**:

1. **`arena_badlands`**
1. **`cp_badlands`**
1. **`koth_badlands`**

### ⚠️ `harvest`

Alphabetical order of **`harvest`**:

1. **`koth_harvest_event`** (Halloween)
1. **`koth_harvest_final`**

### ⚠️ `lakeside`

Alphabetical order of **`lakeside`**:

1. **`koth_lakeside_event`** (Halloween)
1. **`koth_lakeside_final`**
