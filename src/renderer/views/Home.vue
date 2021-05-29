<template>
  <div class="app">
      <div class="header">
        <div class="menu-circle"></div>
        <div class="header-menu">
          <a class="menu-link is-active" href="#">My Workspace</a>
          <a class="menu-link notify" href="#">Discover</a>
        </div>
        <div class="search-bar">
          <input type="text" placeholder="Search" />
        </div>
        <div class="header-profile">
          <div class="notification">
            <span class="notification-number">3</span>
            <svg viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-bell">
            <path d="M18 8A6 6 0 006 8c0 7-3 9-3 9h18s-3-2-3-9M13.73 21a2 2 0 01-3.46 0" />
            </svg>
          </div>
          <svg viewBox="0 0 512 512" fill="currentColor">
            <path d="M448.773 235.551A135.893 135.893 0 00451 211c0-74.443-60.557-135-135-135-47.52 0-91.567 25.313-115.766 65.537-32.666-10.59-66.182-6.049-93.794 12.979-27.612 19.013-44.092 49.116-45.425 82.031C24.716 253.788 0 290.497 0 331c0 7.031 1.703 13.887 3.006 20.537l.015.015C12.719 400.492 56.034 436 106 436h300c57.891 0 106-47.109 106-105 0-40.942-25.053-77.798-63.227-95.449z" />
          </svg>
          <img class="profile-img" src="https://images.unsplash.com/photo-1600353068440-6361ef3a86e8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
        </div>
      </div>
      <div class="wrapper">
        <div class="left-side">
          <div class="side-wrapper">
            <div class="side-menu">
              <a href="#">
                <svg viewBox="0 0 512 512">
                  <g xmlns="http://www.w3.org/2000/svg" fill="currentColor">
                    <path
                      d="M0 0h128v128H0zm0 0M192 0h128v128H192zm0 0M384 0h128v128H384zm0 0M0 192h128v128H0zm0 0"
                      data-original="#bfc9d1"
                    />
                  </g>
                  <path
                    xmlns="http://www.w3.org/2000/svg"
                    d="M192 192h128v128H192zm0 0"
                    fill="currentColor"
                    data-original="#82b1ff"
                  />
                  <path
                    xmlns="http://www.w3.org/2000/svg"
                    d="M384 192h128v128H384zm0 0M0 384h128v128H0zm0 0M192 384h128v128H192zm0 0M384 384h128v128H384zm0 0"
                    fill="currentColor"
                    data-original="#bfc9d1"
                  />
                </svg>
                Dashboard
              </a>
              <a href="#">
                <svg viewBox="0 0 488.932 488.932" fill="currentColor">
                  <path
                    d="M243.158 61.361v-57.6c0-3.2 4-4.9 6.7-2.9l118.4 87c2 1.5 2 4.4 0 5.9l-118.4 87c-2.7 2-6.7.2-6.7-2.9v-57.5c-87.8 1.4-158.1 76-152.1 165.4 5.1 76.8 67.7 139.1 144.5 144 81.4 5.2 150.6-53 163-129.9 2.3-14.3 14.7-24.7 29.2-24.7 17.9 0 31.8 15.9 29 33.5-17.4 109.7-118.5 192-235.7 178.9-98-11-176.7-89.4-187.8-187.4-14.7-128.2 84.9-237.4 209.9-238.8z"
                  />
                </svg>
                Updates
                <span class="notification-number updates">3</span>
              </a>
            </div>
          </div>
          <div class="side-wrapper">
            <div class="side-title">Dev Tools On</div>
            <div class="side-menu">
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M497 151H316c-8.401 0-15 6.599-15 15v300c0 8.401 6.599 15 15 15h181c8.401 0 15-6.599 15-15V166c0-8.401-6.599-15-15-15zm-76 270h-30c-8.401 0-15-6.599-15-15s6.599-15 15-15h30c8.401 0 15 6.599 15 15s-6.599 15-15 15zm0-180h-30c-8.401 0-15-6.599-15-15s6.599-15 15-15h30c8.401 0 15 6.599 15 15s-6.599 15-15 15z"
                  />
                  <path
                    d="M15 331h196v60h-75c-8.291 0-15 6.709-15 15s6.709 15 15 15h135v-30h-30v-60h30V166c0-24.814 20.186-45 45-45h135V46c0-8.284-6.716-15-15-15H15C6.716 31 0 37.716 0 46v270c0 8.284 6.716 15 15 15z"
                  />
                </svg>
                This Mac
              </a>
              <a href="#">
                <svg viewBox="0 0 488.455 488.455" fill="currentColor">
                  <path
                    d="M287.396 216.317c23.845 23.845 23.845 62.505 0 86.35s-62.505 23.845-86.35 0-23.845-62.505 0-86.35 62.505-23.845 86.35 0"
                  />
                  <path
                    d="M427.397 91.581H385.21l-30.544-61.059H133.76l-30.515 61.089-42.127.075C27.533 91.746.193 119.115.164 152.715L0 396.86c0 33.675 27.384 61.074 61.059 61.074h366.338c33.675 0 61.059-27.384 61.059-61.059V152.639c-.001-33.674-27.385-61.058-61.059-61.058zM244.22 381.61c-67.335 0-122.118-54.783-122.118-122.118s54.783-122.118 122.118-122.118 122.118 54.783 122.118 122.118S311.555 381.61 244.22 381.61z"
                  />
                </svg>
                Local Vm
              </a>
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M0 331v112.295a14.996 14.996 0 007.559 13.023L106 512V391L0 331zM136 391v121l105-60V331zM271 331v121l105 60V391zM406 391v121l98.441-55.682A14.995 14.995 0 00512 443.296V331l-106 60zM391 241l-115.754 57.876L391 365.026l116.754-66.15zM262.709 1.583a15.006 15.006 0 00-13.418 0L140.246 57.876 256 124.026l115.754-66.151L262.709 1.583zM136 90v124.955l105 52.5V150zM121 241L4.246 298.876 121 365.026l115.754-66.15zM271 150v117.455l105-52.5V90z"
                  />
                </svg>
                App Container
              </a>
            </div>
          </div>
          <div class="side-wrapper">
            <div class="side-title">Integrations</div>
            <div class="side-menu">
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M467 0H45C20.186 0 0 20.186 0 45v422c0 24.814 20.186 45 45 45h422c24.814 0 45-20.186 45-45V45c0-24.814-20.186-45-45-45zM181 241c41.353 0 75 33.647 75 75s-33.647 75-75 75-75-33.647-75-75c0-8.291 6.709-15 15-15s15 6.709 15 15c0 24.814 20.186 45 45 45s45-20.186 45-45-20.186-45-45-45c-41.353 0-75-33.647-75-75s33.647-75 75-75 75 33.647 75 75c0 8.291-6.709 15-15 15s-15-6.709-15-15c0-24.814-20.186-45-45-45s-45 20.186-45 45 20.186 45 45 45zm180 120h30c8.291 0 15 6.709 15 15s-6.709 15-15 15h-30c-24.814 0-45-20.186-45-45V211h-15c-8.291 0-15-6.709-15-15s6.709-15 15-15h15v-45c0-8.291 6.709-15 15-15s15 6.709 15 15v45h45c8.291 0 15 6.709 15 15s-6.709 15-15 15h-45v135c0 8.276 6.724 15 15 15z"
                  />
                </svg>
                Github
              </a>
              <a href="#">
                <svg viewBox="0 0 511.441 511.441" fill="currentColor">
                  <path
                    d="M255.721 347.484L90.22 266.751v106.57l165.51 73.503 165.509-73.503V266.742z"
                  />
                  <path
                    d="M511.441 189.361L255.721 64.617 0 189.361l255.721 124.744 195.522-95.378v111.032h30V204.092z"
                  />
                </svg>
                Jira
              </a>
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M196 151h-75v90h75c24.814 0 45-20.186 45-45s-20.186-45-45-45z"
                  />
                  <path
                    d="M467 0H45C20.186 0 0 20.186 0 45v422c0 24.814 20.186 45 45 45h422c24.814 0 45-20.186 45-45V45c0-24.814-20.186-45-45-45zM196 271h-75v105c0 8.291-6.709 15-15 15s-15-6.709-15-15V136c0-8.291 6.709-15 15-15h90c41.353 0 75 33.647 75 75s-33.647 75-75 75zm210-60c8.291 0 15 6.709 15 15s-6.709 15-15 15h-45v135c0 8.291-6.709 15-15 15s-15-6.709-15-15V241h-15c-8.291 0-15-6.709-15-15s6.709-15 15-15h15v-45c0-24.814 20.186-45 45-45h30c8.291 0 15 6.709 15 15s-6.709 15-15 15h-30c-8.276 0-15 6.724-15 15v45h45z"
                  />
                </svg>
                AWS
              </a>
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M181 181h-60v60h60c16.54 0 30-13.46 30-30s-13.46-30-30-30zm0 0M181 271h-60v60h60c16.54 0 30-13.46 30-30s-13.46-30-30-30zm0 0M346 241c-19.555 0-36.238 12.54-42.438 30h84.875c-6.199-17.46-22.882-30-42.437-30zm0 0"
                  />
                  <path
                    d="M436 0H75C33.648 0 0 33.648 0 75v362c0 41.352 33.648 75 75 75h361c41.352 0 76-33.648 76-75V75c0-41.352-34.648-75-76-75zM286 151h120v30H286zm-45 150c0 33.09-26.91 60-60 60H91V151h90c33.09 0 60 26.91 60 60 0 18.008-8.133 33.996-20.73 45 12.597 11.004 20.73 26.992 20.73 45zm180 0H303.562c6.196 17.46 22.883 30 42.438 30 16.012 0 30.953-8.629 38.992-22.516l25.957 15.032C397.58 346.629 372.687 361 346 361c-41.352 0-75-33.648-75-75s33.648-75 75-75 75 33.648 75 75zm0 0"
                  />
                </svg>
                Bitbucket
              </a>
              <a href="#">
                <svg viewBox="0 0 512 512" fill="currentColor">
                  <path
                    d="M352 0H64C28.704 0 0 28.704 0 64v320a16.02 16.02 0 009.216 14.496A16.232 16.232 0 0016 400c3.68 0 7.328-1.248 10.24-3.712L117.792 320H352c35.296 0 64-28.704 64-64V64c0-35.296-28.704-64-64-64z"
                  />
                  <path
                    d="M464 128h-16v128c0 52.928-43.072 96-96 96H129.376L128 353.152V400c0 26.464 21.536 48 48 48h234.368l75.616 60.512A16.158 16.158 0 00496 512c2.336 0 4.704-.544 6.944-1.6A15.968 15.968 0 00512 496V176c0-26.464-21.536-48-48-48z"
                  />
                </svg>
                Docker
              </a>
            </div>
          </div>
        </div>
        <div class="main-container">
          <div class="content-wrapper">
            <div class="content-wrapper-header">
              <div class="content-wrapper-context">
                <h3 class="img-content">
                  <svg viewBox="0 0 512 512">
                    <path
                      d="M467 0H45C20.099 0 0 20.099 0 45v422c0 24.901 20.099 45 45 45h422c24.901 0 45-20.099 45-45V45c0-24.901-20.099-45-45-45z"
                      fill="#d6355b"
                      data-original="#ff468c"
                    />
                    <path
                      xmlns="http://www.w3.org/2000/svg"
                      d="M512 45v422c0 24.901-20.099 45-45 45H256V0h211c24.901 0 45 20.099 45 45z"
                      fill="#d6355b"
                      data-original="#d72878"
                    />
                    <path
                      xmlns="http://www.w3.org/2000/svg"
                      d="M467 30H45c-8.401 0-15 6.599-15 15v422c0 8.401 6.599 15 15 15h422c8.401 0 15-6.599 15-15V45c0-8.401-6.599-15-15-15z"
                      fill="#2e000a"
                      data-original="#700029"
                    />
                    <path
                      xmlns="http://www.w3.org/2000/svg"
                      d="M482 45v422c0 8.401-6.599 15-15 15H256V30h211c8.401 0 15 6.599 15 15z"
                      fill="#2e000a"
                      data-original="#4d0e06"
                    />
                    <path
                      xmlns="http://www.w3.org/2000/svg"
                      d="M181 391c-41.353 0-75-33.647-75-75 0-8.291 6.709-15 15-15s15 6.709 15 15c0 24.814 20.186 45 45 45s45-20.186 45-45-20.186-45-45-45c-41.353 0-75-33.647-75-75s33.647-75 75-75 75 33.647 75 75c0 8.291-6.709 15-15 15s-15-6.709-15-15c0-24.814-20.186-45-45-45s-45 20.186-45 45 20.186 45 45 45c41.353 0 75 33.647 75 75s-33.647 75-75 75z"
                      fill="#d6355b"
                      data-original="#ff468c"
                    />
                    <path
                      xmlns="http://www.w3.org/2000/svg"
                      d="M391 361h-30c-8.276 0-15-6.724-15-15V211h45c8.291 0 15-6.709 15-15s-6.709-15-15-15h-45v-45c0-8.291-6.709-15-15-15s-15 6.709-15 15v45h-15c-8.291 0-15 6.709-15 15s6.709 15 15 15h15v135c0 24.814 20.186 45 45 45h30c8.291 0 15-6.709 15-15s-6.709-15-15-15z"
                      fill="#d6355b"
                      data-original="#d72878"
                    />
                  </svg>
                  ButterOps Devbox 
                </h3>
                <div class="content-text">
                  Separate your project infrastructure from that of your Mac. Install a 
                  vagrant based VM with your dev tools in one click.
                </div>
                <button class="content-button">Start One Click Setup</button>
              </div>
              <img
                class="content-wrapper-img"
                src="https://assets.codepen.io/3364143/glass.png"
                alt=""
              />
            </div>
            <div class="content-section">
              <div class="content-section-title">Apps</div>
              <ul>
                <li class="adobe-product">
                  <div class="products">
                    <svg viewBox="0 0 52 52" style="border: 1px solid #3291b8">
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M40.824 52H11.176C5.003 52 0 46.997 0 40.824V11.176C0 5.003 5.003 0 11.176 0h29.649C46.997 0 52 5.003 52 11.176v29.649C52 46.997 46.997 52 40.824 52z"
                          fill="#061e26"
                          data-original="#393687"
                        />
                        <path
                          d="M12.16 39H9.28V11h9.64c2.613 0 4.553.813 5.82 2.44 1.266 1.626 1.9 3.76 1.9 6.399 0 .934-.027 1.74-.08 2.42-.054.681-.22 1.534-.5 2.561-.28 1.026-.66 1.866-1.14 2.52-.48.654-1.213 1.227-2.2 1.72-.987.494-2.16.74-3.52.74h-7.04V39zm0-12h6.68c.96 0 1.773-.187 2.44-.56.666-.374 1.153-.773 1.46-1.2.306-.427.546-1.04.72-1.84.173-.801.267-1.4.28-1.801.013-.399.02-.973.02-1.72 0-4.053-1.694-6.08-5.08-6.08h-6.52V27zM29.48 33.92l2.8-.12c.106.987.6 1.754 1.48 2.3.88.547 1.893.82 3.04.82s2.14-.26 2.98-.78c.84-.52 1.26-1.266 1.26-2.239s-.36-1.747-1.08-2.32c-.72-.573-1.6-1.026-2.64-1.36-1.04-.333-2.086-.686-3.14-1.06a7.36 7.36 0 01-2.78-1.76c-.987-.934-1.48-2.073-1.48-3.42s.54-2.601 1.62-3.761 2.833-1.739 5.26-1.739c.854 0 1.653.1 2.4.3.746.2 1.28.394 1.6.58l.48.279-.92 2.521c-.854-.666-1.974-1-3.36-1-1.387 0-2.42.26-3.1.78-.68.52-1.02 1.18-1.02 1.979 0 .88.426 1.574 1.28 2.08.853.507 1.813.934 2.88 1.28 1.066.347 2.126.733 3.18 1.16 1.053.427 1.946 1.094 2.68 2s1.1 2.106 1.1 3.6c0 1.494-.6 2.794-1.8 3.9-1.2 1.106-2.954 1.66-5.26 1.66-2.307 0-4.114-.547-5.42-1.64-1.307-1.093-1.987-2.44-2.04-4.04z"
                          fill="#c1dbe6"
                          data-original="#89d3ff"
                        />
                      </g>
                    </svg>
                    VirtualBox
                  </div>
                  <span class="status">
                    <span class="status-circle green"></span>
                    Updated</span
                  >
                  <div class="button-wrapper">
                    <button class="content-button status-button open">
                      Open
                    </button>
                    <div class="menu">
                      <button class="dropdown">
                        <ul>
                          <li><a href="#">Go to Discover</a></li>
                          <li><a href="#">Learn more</a></li>
                          <li><a href="#">Uninstall</a></li>
                        </ul>
                      </button>
                    </div>
                  </div>
                </li>
                <li class="adobe-product">
                  <div class="products">
                    <svg viewBox="0 0 52 52" style="border: 1px solid #b65a0b">
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M40.824 52H11.176C5.003 52 0 46.997 0 40.824V11.176C0 5.003 5.003 0 11.176 0h29.649C46.997 0 52 5.003 52 11.176v29.649C52 46.997 46.997 52 40.824 52z"
                          fill="#261400"
                          data-original="#6d4c13"
                        />
                        <path
                          d="M30.68 39h-3.24l-2.76-9.04h-8.32L13.72 39H10.6l8.24-28h3.32l8.52 28zm-6.72-12l-3.48-11.36L17.12 27h6.84zM37.479 12.24c0 .453-.16.84-.48 1.16-.32.319-.7.479-1.14.479-.44 0-.827-.166-1.16-.5-.334-.333-.5-.713-.5-1.14s.166-.807.5-1.141c.333-.333.72-.5 1.16-.5.44 0 .82.16 1.14.48.321.322.48.709.48 1.162zM37.24 39h-2.88V18.96h2.88V39z"
                          fill="#e6d2c0"
                          data-original="#ffbd2e"
                        />
                      </g>
                    </svg>
                    VS Code
                  </div>

                  <span class="status">
                    <span class="status-circle"></span>
                    Update Available</span
                  >
                  <div class="button-wrapper">
                    <button class="content-button status-button">
                      Update this app
                    </button>
                    <div class="pop-up">
                      <div class="pop-up__title">
                        Update This App
                        <svg
                          class="close feather feather-x-circle"
                          width="24"
                          height="24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        >
                          <circle cx="12" cy="12" r="10" />
                          <path d="M15 9l-6 6M9 9l6 6" />
                        </svg>
                      </div>
                      <div class="pop-up__subtitle">
                        Adjust your selections for advanced options as desired
                        before continuing. <a href="#">Learn more</a>
                      </div>
                      <div class="checkbox-wrapper">
                        <input type="checkbox" id="check1" class="checkbox" />
                        <label for="check1"
                          >Import previous settings and preferences</label
                        >
                      </div>
                      <div class="checkbox-wrapper">
                        <input type="checkbox" id="check2" class="checkbox" />
                        <label for="check2">Remove old versions</label>
                      </div>
                      <div class="content-button-wrapper">
                        <button class="content-button status-button open close">
                          Cancel
                        </button>
                        <button class="content-button status-button">
                          Continue
                        </button>
                      </div>
                    </div>
                    <div class="menu">
                      <button class="dropdown">
                        <ul>
                          <li><a href="#">Go to Discover</a></li>
                          <li><a href="#">Learn more</a></li>
                          <li><a href="#">Uninstall</a></li>
                        </ul>
                      </button>
                    </div>
                  </div>
                </li>
                <li class="adobe-product">
                  <div class="products">
                    <svg viewBox="0 0 52 52" style="border: 1px solid #c75deb">
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M40.824 52H11.176C5.003 52 0 46.997 0 40.824V11.176C0 5.003 5.003 0 11.176 0h29.649C46.997 0 52 5.003 52 11.176v29.649C52 46.997 46.997 52 40.824 52z"
                          fill="#3a3375"
                          data-original="#3a3375"
                        />
                        <path
                          d="M27.44 39H24.2l-2.76-9.04h-8.32L10.48 39H7.36l8.24-28h3.32l8.52 28zm-6.72-12l-3.48-11.36L13.88 27h6.84zM31.48 33.48c0 2.267 1.333 3.399 4 3.399 1.653 0 3.466-.546 5.44-1.64L42 37.6c-2.054 1.254-4.2 1.881-6.44 1.881-4.64 0-6.96-1.946-6.96-5.841v-8.2c0-2.16.673-3.841 2.02-5.04 1.346-1.2 3.126-1.801 5.34-1.801s3.94.594 5.18 1.78c1.24 1.187 1.86 2.834 1.86 4.94V30.8l-11.52.6v2.08zm8.6-5.24v-3.08c0-1.413-.44-2.42-1.32-3.021-.88-.6-1.907-.899-3.08-.899-1.174 0-2.167.359-2.98 1.08-.814.72-1.22 1.773-1.22 3.16v3.199l8.6-.439z"
                          fill="#e4d1eb"
                          data-original="#e7adfb"
                        />
                      </g>
                    </svg>
                    Docker Desktop
                  </div>
                  <span class="status">
                    <span class="status-circle green"></span>
                    Updated</span
                  >
                  <div class="button-wrapper">
                    <button class="content-button status-button open">
                      Open
                    </button>
                    <div class="menu">
                      <button class="dropdown">
                        <ul>
                          <li><a href="#">Go to Discover</a></li>
                          <li><a href="#">Learn more</a></li>
                          <li><a href="#">Uninstall</a></li>
                        </ul>
                      </button>
                    </div>
                  </div>
                </li>

              </ul>
            </div>
            <div class="content-section">
              <div class="content-section-title">Dev Environments</div>
              <div class="apps-card">
                <div class="app-card">
                  <span>
                    <svg
                      viewBox="0 0 512 512"
                      style="border: 1px solid #a059a9"
                    >
                      <path
                        xmlns="http://www.w3.org/2000/svg"
                        d="M480 0H32C14.368 0 0 14.368 0 32v448c0 17.664 14.368 32 32 32h448c17.664 0 32-14.336 32-32V32c0-17.632-14.336-32-32-32z"
                        fill="#210027"
                        data-original="#7b1fa2"
                      />
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M192 64h-80c-8.832 0-16 7.168-16 16v352c0 8.832 7.168 16 16 16s16-7.168 16-16V256h64c52.928 0 96-43.072 96-96s-43.072-96-96-96zm0 160h-64V96h64c35.296 0 64 28.704 64 64s-28.704 64-64 64zM400 256h-32c-18.08 0-34.592 6.24-48 16.384V272c0-8.864-7.168-16-16-16s-16 7.136-16 16v160c0 8.832 7.168 16 16 16s16-7.168 16-16v-96c0-26.464 21.536-48 48-48h32c8.832 0 16-7.168 16-16s-7.168-16-16-16z"
                          fill="#f6e7fa"
                          data-original="#e1bee7"
                        />
                      </g>
                    </svg>
                    Node
                  </span>
                  <div class="app-card__subtext">
                    Edit, master and create fully proffesional videos
                  </div>
                  <div class="app-card-buttons">
                    <button class="content-button status-button">Update</button>
                    <div class="menu"></div>
                  </div>
                </div>
                <div class="app-card">
                  <span>
                    <svg viewBox="0 0 52 52" style="border: 1px solid #c1316d">
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M40.824 52H11.176C5.003 52 0 46.997 0 40.824V11.176C0 5.003 5.003 0 11.176 0h29.649C46.997 0 52 5.003 52 11.176v29.649C52 46.997 46.997 52 40.824 52z"
                          fill="#2f0015"
                          data-original="#6f2b41"
                        />
                        <path
                          d="M18.08 39H15.2V13.72l-2.64-.08V11h5.52v28zM27.68 19.4c1.173-.507 2.593-.761 4.26-.761s3.073.374 4.22 1.12V11h2.88v28c-2.293.32-4.414.48-6.36.48-1.947 0-3.707-.4-5.28-1.2-2.08-1.066-3.12-2.92-3.12-5.561v-7.56c0-2.799 1.133-4.719 3.4-5.759zm8.48 3.12c-1.387-.746-2.907-1.119-4.56-1.119-1.574 0-2.714.406-3.42 1.22-.707.813-1.06 1.847-1.06 3.1v7.12c0 1.227.44 2.188 1.32 2.88.96.719 2.146 1.079 3.56 1.079 1.413 0 2.8-.106 4.16-.319V22.52z"
                          fill="#e1c1cf"
                          data-original="#ff70bd"
                        />
                      </g>
                    </svg>
                    Python
                  </span>
                  <div class="app-card__subtext">
                    Design and publish great projects & mockups
                  </div>
                  <div class="app-card-buttons">
                    <button class="content-button status-button">Update</button>
                    <div class="menu"></div>
                  </div>
                </div>
                <div class="app-card">
                  <span>
                    <svg viewBox="0 0 52 52" style="border: 1px solid #c75deb">
                      <g xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M40.824 52H11.176C5.003 52 0 46.997 0 40.824V11.176C0 5.003 5.003 0 11.176 0h29.649C46.997 0 52 5.003 52 11.176v29.649C52 46.997 46.997 52 40.824 52z"
                          fill="#3a3375"
                          data-original="#3a3375"
                        />
                        <path
                          d="M27.44 39H24.2l-2.76-9.04h-8.32L10.48 39H7.36l8.24-28h3.32l8.52 28zm-6.72-12l-3.48-11.36L13.88 27h6.84zM31.48 33.48c0 2.267 1.333 3.399 4 3.399 1.653 0 3.466-.546 5.44-1.64L42 37.6c-2.054 1.254-4.2 1.881-6.44 1.881-4.64 0-6.96-1.946-6.96-5.841v-8.2c0-2.16.673-3.841 2.02-5.04 1.346-1.2 3.126-1.801 5.34-1.801s3.94.594 5.18 1.78c1.24 1.187 1.86 2.834 1.86 4.94V30.8l-11.52.6v2.08zm8.6-5.24v-3.08c0-1.413-.44-2.42-1.32-3.021-.88-.6-1.907-.899-3.08-.899-1.174 0-2.167.359-2.98 1.08-.814.72-1.22 1.773-1.22 3.16v3.199l8.6-.439z"
                          fill="#e4d1eb"
                          data-original="#e7adfb"
                        />
                      </g>
                    </svg>
                    Docker
                  </span>
                  <div class="app-card__subtext">
                    Industry Standart motion graphics & visual effects
                  </div>
                  <div class="app-card-buttons">
                    <button class="content-button status-button">Update</button>
                    <div class="menu"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="overlay-app"></div>
  </div>
</template>

<script>
var $ = require('jquery')
import Vue from 'vue'

export default Vue.extend({
  name: 'About',
  mounted: () => {
    $(function () {
      $('.menu-link').click(function () {
        $('.menu-link').removeClass('is-active')
        $(this).addClass('is-active')
      })
    })

    $(function () {
      $('.main-header-link').click(function () {
        $('.main-header-link').removeClass('is-active')
        $(this).addClass('is-active')
      })
    })

    const dropdowns = document.querySelectorAll('.dropdown')
    dropdowns.forEach((dropdown) => {
      dropdown.addEventListener('click', (e) => {
        e.stopPropagation()
        dropdowns.forEach((c) => c.classList.remove('is-active'))
        dropdown.classList.add('is-active')
      })
    })

    $('.search-bar input')
      .focus(function () {
        $('.header').addClass('wide')
      })
      .blur(function () {
        $('.header').removeClass('wide')
      })

    $(document).click(function (e) {
      var container = $('.status-button')
      var dd = $('.dropdown')
      if (!container.is(e.target) && container.has(e.target).length === 0) {
        dd.removeClass('is-active')
      }
    })

    $(function () {
      $('.dropdown').on('click', function (e) {
        $('.content-wrapper').addClass('overlay')
        e.stopPropagation()
      })

      $(document).on('click', function (e) {
        if ($(e.target).is('.dropdown') === false) {
          $('.content-wrapper').removeClass('overlay')
        }
      })
    })

    $(function () {
      $('.status-button:not(.open)').on('click', function (e) {
        $('.overlay-app').addClass('is-active')
      })
      $('.pop-up .close').click(function () {
        $('.overlay-app').removeClass('is-active')
      })
    })

    $('.status-button:not(.open)').click(function () {
      $('.pop-up').addClass('visible')
    })

    $('.pop-up .close').click(function () {
      $('.pop-up').removeClass('visible')
    })

  }

})
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');

* {
  outline: none;
  box-sizing: border-box;
}

:root {
  --theme-bg-color: rgba(16 18 27 / 20%);
  --border-color: rgba(113 119 144 / 25%);
  --theme-color: #f9fafb;
  --inactive-color: rgb(113 119 144 / 78%);
  --body-font: 'Poppins', sans-serif;
  --hover-menu-bg: rgba(12 15 25 / 30%);
  --content-title-color: #999ba5;
  --content-bg: rgb(146 151 179 / 13%);
  --button-inactive: rgb(249 250 251 / 55%);
  --dropdown-bg: #21242d;
  --dropdown-hover: rgb(42 46 60);
  --popup-bg: rgb(22 25 37);
  --search-bg: #14162b;
  --overlay-bg: rgba(36, 39, 59, 0.3);
  --scrollbar-bg: rgb(1 2 3 / 40%);
}


html {
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
}

body {
  font-family: var(--body-font);
  // background-image: url(https://4kwallpapers.com/images/wallpapers/samsung-galaxy-s11-blue-stock-bubble-gradients-3040x3040-1705.jpg);
  background-color: var(--theme-bg-color);
  background-size: cover;
  background-position: center;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  //  padding: 2em;
  width: 100%;
  height: 100vh;
  //  @media screen and (max-width: 480px) {
  //   padding: 0.8em;
  //  }
  margin: 0;
}

img {
  max-width: 100%;
}

.app {
  background-color: var(--theme-bg-color);
  //  max-width: 1250px;
  //  max-height: 860px;
  height: 100vh;
  display: flex;
  flex-direction: column;
  overflow: hidden;
  width: 100vW;
  //  border-radius: 14px;
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  font-size: 15px;
  font-weight: 500;
}

.header {
  display: flex;
  align-items: center;
  flex-shrink: 0;
  height: 58px;
  width: 100%;
  border-bottom: 1px solid var(--border-color);
  padding: 0 30px;
  white-space: nowrap;
  -webkit-app-region: drag;
  @media screen and (max-width: 480px) {
    padding: 0 16px;
  }
  &-menu {
    display: flex;
    align-items: center;
    a {
      padding: 20px 30px;
      text-decoration: none;
      color: var(--inactive-color);
      border-bottom: 2px solid transparent;
      transition: 0.3s;
      @media screen and (max-width: 610px) {
        &:not(.main-header-link) {
          display: none;
        }
      }
      &.is-active,
      &:hover {
        color: var(--theme-color);
        border-bottom: 2px solid var(--theme-color);
      }
    }
  }
}

.notify {
  position: relative;
  &:before {
    content: '';
    position: absolute;
    background-color: #3a6df0;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    right: 20px;
    top: 16px;
  }
  @media screen and (max-width: 1055px) {
    display: none;
  }
}

.menu-circle {
  width: 15px;
  height: 15px;
  // background-color: #f96057;
  border-radius: 50%;
  // box-shadow: 24px 0 0 0 #f8ce52, 48px 0 0 0 #5fcf65;
  margin-right: 155px;
  flex-shrink: 0;
  @media screen and (max-width: 945px) {
    display: none;
  }
}

.search-bar {
  height: 40px;
  display: flex;
  width: 100%;
  max-width: 400px;
  padding-left: 16px;
  border-radius: 4px;
  input {
    width: 100%;
    height: 100%;
    border: none;
    background-color: var(--search-bg);
    border-radius: 4px;
    font-family: var(--body-font);
    font-size: 15px;
    font-weight: 500;
    padding: 0 20px 0 40px;
    box-shadow: 0 0 0 2px rgb(134 140 160 / 2%);
    background-image: url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 56.966 56.966' fill='%23717790c7'%3e%3cpath d='M55.146 51.887L41.588 37.786A22.926 22.926 0 0046.984 23c0-12.682-10.318-23-23-23s-23 10.318-23 23 10.318 23 23 23c4.761 0 9.298-1.436 13.177-4.162l13.661 14.208c.571.593 1.339.92 2.162.92.779 0 1.518-.297 2.079-.837a3.004 3.004 0 00.083-4.242zM23.984 6c9.374 0 17 7.626 17 17s-7.626 17-17 17-17-7.626-17-17 7.626-17 17-17z'/%3e%3c/svg%3e");
    background-size: 14px;
    background-repeat: no-repeat;
    background-position: 16px 48%;
    color: var(--theme-color);
    &::placeholder {
      font-family: var(--body-font);
      color: var(--inactive-color);
      font-size: 15px;
      font-weight: 500;
    }
  }
}

.header-profile {
  display: flex;
  align-items: center;
  padding: 0 16px 0 40px;
  margin-left: auto;
  flex-shrink: 0;
  svg {
    width: 22px;
    color: #f9fafb;
    flex-shrink: 0;
  }
}

.notification {
  position: relative;
  &-number {
    position: absolute;
    background-color: #3a6df0;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    font-size: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    right: -6px;
    top: -6px;
  }
  & + svg {
    margin-left: 22px;
    @media screen and (max-width: 945px) {
      display: none;
    }
  }
}

.profile-img {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  object-fit: cover;
  border: 2px solid var(--theme-color);
  margin-left: 22px;
}

.wide {
  .header-menu,
  .header-profile {
    display: none;
  }
  .search-bar {
    max-width: 600px;
    margin: auto;
    transition: 0.4s;
    box-shadow: 0 0 0 1px var(--border-color);
    padding-left: 0;
  }
  .menu-circle {
    margin-right: 0;
  }
}

.wrapper {
  display: flex;
  flex-grow: 1;
  overflow: hidden;
}

.left-side {
  flex-basis: 200px;
  border-right: 1px solid var(--border-color);
  padding: 26px;
  overflow: auto;
  flex-shrink: 0;
  @media screen and (max-width: 945px) {
    display: none;
  }
}

.side-wrapper + .side-wrapper {
  margin-top: 20px;
}

.side-title {
  color: var(--inactive-color);
  margin-bottom: 14px;
}

.side-menu {
  display: flex;
  flex-direction: column;
  white-space: nowrap;
  a {
    text-decoration: none;
    color: var(--theme-color);
    display: flex;
    align-items: center;
    font-weight: 400;
    padding: 10px;
    font-size: 14px;
    border-radius: 6px;
    transition: 0.3s;
    &:hover {
      background-color: var(--hover-menu-bg);
    }
  }
  svg {
    width: 16px;
    margin-right: 8px;
  }
}

.updates {
  position: relative;
  top: 0;
  right: 0;
  margin-left: auto;
  width: 18px;
  height: 18px;
  font-size: 11px;
}

.main-header {
  display: flex;
  align-items: center;
  border-bottom: 1px solid var(--border-color);
  height: 58px;
  flex-shrink: 0;
  .header-menu {
    margin-left: 150px;
    @media screen and (max-width: 1055px) {
      margin: auto;
    }
    a {
      padding: 20px 24px;
    }
  }
}

.main-container {
  background-color: #282828;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.menu-link-main {
  text-decoration: none;
  color: var(--theme-color);
  padding: 0 30px;
  @media screen and (max-width: 1055px) {
    display: none;
  }
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  color: var(--theme-color);
  padding: 20px 40px;
  height: 100%;
  overflow: auto;
  background-color: var(--theme-bg-color);
  @media screen and (max-width: 510px) {
    padding: 20px;
  }
  &-header {
    display: flex;
    align-items: center;
    width: 100%;
    justify-content: space-between;
    background-image: url('https://www.transparenttextures.com/patterns/cubes.png'),
      linear-gradient(
        to right top,
        #cf4af3,
        #e73bd7,
        #f631bc,
        #fd31a2,
        #ff3a8b,
        #ff4b78,
        #ff5e68,
        #ff705c,
        #ff8c51,
        #ffaa49,
        #ffc848,
        #ffe652
      );
    border-radius: 14px;
    padding: 20px 40px;
    @media screen and (max-width: 415px) {
      padding: 20px;
    }
  }
  &.overlay {
    pointer-events: none;
    transition: 0.3s;
    background-color: var(--overlay-bg);
  }
}

.overlay-app {
  width: 100%;
  height: 100%;
  position: fixed;
  left: 0;
  top: 0;
  pointer-events: all;
  background-color: rgba(36, 39, 59, 0.8);
  opacity: 0;
  visibility: hidden;
  transition: 0.3s;
  &.is-active {
    visibility: visible;
    opacity: 1;
  }
}

.img-content {
  font-weight: 500;
  font-size: 17px;
  display: flex;
  align-items: center;
  margin: 0;
  svg {
    width: 28px;
    margin-right: 14px;
  }
}

.content-text {
  font-weight: 400;
  font-size: 14px;
  margin-top: 16px;
  line-height: 1.7em;
  color: #ebecec;
  display: -webkit-box;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
}

.content-wrapper-context {
  max-width: 350px;
}

.content-button {
  background-color: #3a6df0;
  border: none;
  padding: 8px 26px;
  color: #fff;
  border-radius: 20px;
  margin-top: 16px;
  cursor: pointer;
  transition: 0.3s;
  white-space: nowrap;
}

.content-wrapper-img {
  width: 186px;
  object-fit: cover;
  margin-top: -25px;
  object-position: center;
  @media screen and (max-width: 570px) {
    width: 110px;
  }
}

.content-section {
  margin-top: 30px;
  display: flex;
  flex-direction: column;
  &-title {
    color: var(--content-title-color);
    margin-bottom: 14px;
  }
  ul {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100%;
    justify-content: space-around;
    background-color: var(--content-bg);
    padding-left: 0;
    margin: 0;
    border-radius: 14px;
    border: 1px solid var(--theme-bg-color);
    cursor: pointer;
    li {
      list-style: none;
      padding: 10px 18px;
      display: flex;
      align-items: center;
      font-size: 16px;
      width: 100%;
      height: 100%;
      white-space: nowrap;
      transition: 0.3s;
      &:hover {
        background-color: var(--theme-bg-color);
        &:first-child {
          border-radius: 13px 13px 0 0;
        }
        &:last-child {
          border-radius: 0 0 13px 13px;
        }
      }
      & + li {
        border-top: 1px solid var(--border-color);
      }
    }
    svg {
      width: 28px;
      border-radius: 6px;
      margin-right: 16px;
      flex-shrink: 0;
    }
  }
}

.products {
  display: flex;
  align-items: center;
  width: 150px;
  @media screen and (max-width: 480px) {
    width: 120px;
  }
}
.status {
  margin-left: auto;
  width: 140px;
  font-size: 15px;
  position: relative;
  @media screen and (max-width: 700px) {
    display: none;
  }
  &-circle {
    width: 6px;
    height: 6px;
    background-color: #396df0;
    position: absolute;
    border-radius: 50%;
    top: 4px;
    left: -20px;
    &.green {
      background-color: #3bf083;
    }
  }
  &-button {
    font-size: 15px;
    margin-top: 0;
    padding: 6px 24px;
    @media screen and (max-width: 390px) {
      padding: 6px 14px;
    }
    &.open {
      background: none;
      color: var(--button-inactive);
      border: 1px solid var(--button-inactive);
    }
    &:not(.open):hover {
      color: #fff;
      border-color: #fff;
    }
  }
}

.content-button:not(.open):hover {
  background: #1e59f1;
}

.menu {
  width: 5px;
  height: 5px;
  background-color: var(--button-inactive);
  border-radius: 50%;
  box-shadow: 7px 0 0 0 var(--button-inactive),
    14px 0 0 0 var(--button-inactive);
  margin: 0 12px;
}

@media screen and (max-width: 415px) {
  .adobe-product .menu {
    display: none;
  }
}

.dropdown {
  position: relative;
  height: 53px;
  width: 40px;
  top: -24px;
  display: flex;
  left: -5px;
  background: transparent;
  border: none;
  cursor: pointer;
  ul {
    position: absolute;
    background: var(--dropdown-bg);
    height: 110px;
    width: 120px;
    right: 0;
    top: 20px;
    pointer-events: none;
    opacity: 0;
    transform: translatey(10px);
    transition: all 0.4s ease;
    li a {
      text-decoration: none;
      color: var(--theme-color);
      font-size: 12px;
    }
  }
}

.dropdown.is-active {
  ul {
    opacity: 1;
    pointer-events: all;
    transform: translatey(25px);
    li:hover {
      background-color: var(--dropdown-hover);
    }
  }
}

.button-wrapper {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  width: 187px;
  margin-left: auto;
  @media screen and (max-width: 480px) {
    width: auto;
  }
}

.pop-up {
  position: absolute;
  padding: 30px 40px;
  top: 50%;
  left: 50%;
  transform: (translate(-50%, -50%));
  overflow-y: auto;
  box-shadow: 0px 6px 30px rgba(0, 0, 0, 0.4);
  transition: all 0.3s;
  z-index: 10;
  background-color: var(--popup-bg);
  width: 500px;
  visibility: hidden;
  opacity: 0;
  border-radius: 6px;
  display: flex;
  flex-direction: column;
  white-space: normal;
  @media screen and (max-width: 570px) {
    width: 100%;
  }
  &.visible {
    visibility: visible;
    opacity: 1;
  }
  &__title {
    padding-bottom: 20px;
    border-bottom: 1px solid var(--border-color);
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  &__subtitle {
    white-space: normal;
    margin: 20px 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.8em;
    a {
      color: var(--theme-color);
    }
  }
}

.content-button-wrapper .content-button.status-button.open.close {
  width: auto;
}

.content-section .close {
  margin-right: 0;
  width: 24px;
}

.checkbox-wrapper {
  display: flex;
  align-items: center;
  font-size: 14px;
  font-weight: 400;
  & + .checkbox-wrapper {
    margin: 20px 0 40px;
  }
}

.checkbox {
  display: none;
}

.checkbox + label {
  display: flex;
  align-items: center;
  &:before {
    content: '';
    margin-right: 10px;
    width: 15px;
    height: 15px;
    border: 1px solid var(--theme-color);
    border-radius: 4px;
    cursor: pointer;
    flex-shrink: 0;
  }
}

.checkbox:checked + label:before {
  background-color: #3a6df0;
  border-color: #3a6df0;
  background-image: url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='%23fff' stroke-width='3' stroke-linecap='round' stroke-linejoin='round' class='feather feather-check'%3e%3cpath d='M20 6L9 17l-5-5'/%3e%3c/svg%3e");
  background-position: 50%;
  background-size: 12px;
  background-repeat: no-repeat;
}

.content-button-wrapper {
  margin-top: auto;
  margin-left: auto;
  .open {
    margin-right: 8px;
  }
}

.apps-card {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  width: calc(100% + 20px);
}

.app-card {
  display: flex;
  flex-direction: column;
  width: calc(33.3% - 20px);
  font-size: 16px;
  background-color: var(--content-bg);
  border-radius: 14px;
  border: 1px solid var(--theme-bg-color);
  padding: 20px;
  cursor: pointer;
  transition: 0.3s ease;
  &:hover {
    transform: scale(1.02);
    background-color: var(--theme-bg-color);
  }
  svg {
    width: 28px;
    border-radius: 6px;
    margin-right: 12px;
    flex-shrink: 0;
  }
  & + .app-card {
    margin-left: 20px;
  }
  span {
    display: flex;
    align-items: center;
  }
  &__subtext {
    font-size: 14px;
    font-weight: 400;
    line-height: 1.6em;
    margin-top: 20px;
    border-bottom: 1px solid var(--border-color);
    padding-bottom: 20px;
  }
  &-buttons {
    display: flex;
    align-items: center;
    margin-left: auto;
    margin-top: 16px;
  }
  @media screen and (max-width: 1110px) {
    width: calc(50% - 20px);
    &:last-child {
      margin-top: 20px;
      margin-left: 0px;
    }
  }
  @media screen and (max-width: 565px) {
    width: calc(100% - 20px);
    margin-top: 20px;
    & + .app-card {
      margin-left: 0;
    }
  }
}

::-webkit-scrollbar {
  width: 3px;
  border-radius: 3px;
}

::-webkit-scrollbar-thumb {
  background: var(--scrollbar-bg);
  border-radius: 3px;
}
</style>
