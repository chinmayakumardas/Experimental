<style>
  .category-row {
    display: flex;
    gap: 20px;
    justify-content: space-between;
    margin-bottom: 40px;
  }

  .category-table {
    width: 100%;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border: 2px solid #ccc;
    transition: all 0.3s ease;
  }

  .category-table:hover {
    transform: scale(1.05);
  }

  .category-table th,
  .category-table td {
    padding: 12px;
    text-align: left;
  }

  .category-table th {
    background-color: #0F0F0F;
    color: #F9F7F4;
  }

  .category-table td {
    background-color: #F9F7F4;
    color: #0F0F0F;
  }

  .category-table a {
    text-decoration: none;
    color: #0066cc;
    transition: color 0.3s ease;
  }

  .category-table a:hover {
    color: #ff6600;
  }

  .category-heading {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 12px;
    color: #0F0F0F;
  }

  .category-heading span {
    margin-left: 10px;
  }

  .category-item {
    background-color: #F9F7F4;
    color: #0F0F0F;
    padding: 12px;
    border-radius: 8px;
    border: 2px solid #ccc;
    cursor: pointer;
    font-size: 18px;
    transition: background-color 0.3s ease;
  }

  .category-item:hover {
    background-color: #0F0F0F;
    color: #F9F7F4;
  }

  .category-grid {
    display: flex;
    gap: 20px;
    margin-bottom: 20px;
  }

  .category-item:focus {
    outline: none;
  }
</style>

<div class="category-grid">
    <button class="category-item" onclick="window.location.href='#ui-components'">UI Components</button>
    <button class="category-item" onclick="window.location.href='#documentation'">Documentation</button>
    <button class="category-item" onclick="window.location.href='#social-profiles'">Social Profiles</button>
    <button class="category-item" onclick="window.location.href='#color'">Color</button>
</div>

<!-- Row with two categories: Social Profiles and Color -->
<div class="category-row">
  <!-- Social Profiles Section -->
  <section id="social-profiles" class="category-table">
      <h2 class="category-heading">🌐 Social Profiles <span>👥</span></h2>
      <table>
          <thead>
              <tr>
                  <th>Tool/Website Name</th>
                  <th>Description</th>
                  <th>Link</th>
              </tr>
          </thead>
          <tbody>
              <tr>
                  <td><strong><a href="https://www.linkedin.com/" target="_blank">LinkedIn</a></strong></td>
                  <td>Professional network</td>
                  <td><a href="https://www.linkedin.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://github.com/" target="_blank">GitHub</a></strong></td>
                  <td>Code repository</td>
                  <td><a href="https://github.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://twitter.com/" target="_blank">Twitter</a></strong></td>
                  <td>Networking platform</td>
                  <td><a href="https://twitter.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.facebook.com/" target="_blank">Facebook</a></strong></td>
                  <td>Social networking</td>
                  <td><a href="https://www.facebook.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.instagram.com/" target="_blank">Instagram</a></strong></td>
                  <td>Image sharing</td>
                  <td><a href="https://www.instagram.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.reddit.com/" target="_blank">Reddit</a></strong></td>
                  <td>Social news</td>
                  <td><a href="https://www.reddit.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.quora.com/" target="_blank">Quora</a></strong></td>
                  <td>Q&A platform</td>
                  <td><a href="https://www.quora.com/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.pinterest.com/" target="_blank">Pinterest</a></strong></td>
                  <td>Image board</td>
                  <td><a href="https://www.pinterest.com/" target="_blank">Click here</a></td>
              </tr>
          </tbody>
      </table>
  </section>

  <!-- Color Section -->
  <section id="color" class="category-table">
      <h2 class="category-heading">🎨 Color <span>🌈</span></h2>
      <table>
          <thead>
              <tr>
                  <th>Tool/Website Name</th>
                  <th>Description</th>
                  <th>Link</th>
              </tr>
          </thead>
          <tbody>
              <tr>
                  <td><strong><a href="https://coolors.co/" target="_blank">Coolors</a></strong></td>
                  <td>Palette generator</td>
                  <td><a href="https://coolors.co/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://colorhunt.co/" target="_blank">Color Hunt</a></strong></td>
                  <td>Color palettes</td>
                  <td><a href="https://colorhunt.co/" target="_blank">Click here</a></td>
              </tr>
              <tr>
                  <td><strong><a href="https://www.materialui.co/colors" target="_blank">Material UI Colors</a></strong></td>
                  <td>Material design colors</td>
                  <td><a href="https://www.materialui.co/colors" target="_blank">Click here</a></td>
              </tr>
          </tbody>
      </table>
  </section>
</div>
