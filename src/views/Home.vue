<template>
  <div>
    <nav class="navbar orange lighten-1">
      <div class="nav-wrapper">
        <div class="navbar-left">
          <a href="#">
            <i class="material-icons black-text">dehaze</i>
          </a>
          <span class="black-text">12.12.12</span>
        </div>

        <ul class="right hide-on-small-and-down">
          <li>
            <a
              class="dropdown-trigger black-text"
              href="#"
              data-target="dropdown"
            >
              USER NAME
              <i class="material-icons right">arrow_drop_down</i>
            </a>

            <ul id="dropdown" class="dropdown-content">
              <li>
                <a href="#" class="black-text">
                  <i class="material-icons">account_circle</i>Профиль
                </a>
              </li>
              <li class="divider" tabindex="-1"></li>
              <li>
                <a href="#" class="black-text">
                  <i class="material-icons">assignment_return</i>Выйти
                </a>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </nav>

    <ul class="sidenav app-sidenav open">
      <li>
        <a href="#" class="waves-effect waves-orange pointer">Счет</a>
      </li>
      <li>
        <a href="#" class="waves-effect waves-orange pointer">История</a>
      </li>
      <li>
        <a href="#" class="waves-effect waves-orange pointer">Планирование</a>
      </li>
      <li>
        <a href="#" class="waves-effect waves-orange pointer">Новая запись</a>
      </li>
      <li>
        <a href="#" class="waves-effect waves-orange pointer">Категории</a>
      </li>
    </ul>

    <main class="app-content">
      <div class="app-page">
        <div>
          <div class="page-title">
            <h3>Счет</h3>

            <button class="btn waves-effect waves-light btn-small">
              <i class="material-icons">refresh</i>
            </button>
          </div>

          <div class="row">
            <div class="col s12 m6 l4">
              <div class="card light-blue bill-card">
                <div class="card-content white-text">
                  <span class="card-title">Счет в валюте</span>

                  <p class="currency-line">
                    <span>12.0 Р</span>
                  </p>
                </div>
              </div>
            </div>

            <div class="col s12 m6 l8">
              <div class="card orange darken-3 bill-card">
                <div class="card-content white-text">
                  <div class="card-header">
                    <span class="card-title">Курс валют</span>
                  </div>
                  <table>
                    <thead>
                      <tr>
                        <th>Валюта</th>
                        <th>Курс</th>
                        <th>Дата</th>
                      </tr>
                    </thead>

                    <tbody>
                      <tr>
                        <td>руб</td>
                        <td>12121</td>
                        <td>12.12.12</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>

    <div class="fixed-action-btn">
      <a class="btn-floating btn-large blue" href="#">
        <i class="large material-icons">add</i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
};
</script>
