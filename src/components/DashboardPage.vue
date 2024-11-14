<template>
  <div>
    <aside
      class="sidenav navbar navbar-vertical navbar-expand-xs border-0 border-radius-xl my-3 fixed-start ms-3"
      id="sidenav-main"
    >
      <div class="sidenav-header">
        <i
          class="fas fa-times p-3 cursor-pointer text-secondary opacity-5 position-absolute end-0 top-0 d-none d-xl-none"
          aria-hidden="true"
          id="iconSidenav"
        ></i>
        <a class="navbar-brand m-0" href="/">
          <img src="logo.png" class="navbar-brand-img h-100" alt="main_logo" />
          <span class="ms-1 font-weight-bold">Komgrip Technologies</span>
        </a>
      </div>
      <hr class="horizontal dark mt-0" />
      <div
        class="collapse navbar-collapse w-auto max-height-vh-100 h-100"
        id="sidenav-collapse-main"
      >
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="/">
              <div
                class="icon icon-shape icon-sm shadow border-radius-md bg-white text-center me-2 d-flex align-items-center justify-content-center"
              >
                <svg
                  width="12px"
                  height="12px"
                  viewBox="0 0 45 40"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                >
                  <title>shop</title>
                  <g
                    stroke="none"
                    stroke-width="1"
                    fill="none"
                    fill-rule="evenodd"
                  >
                    <g
                      transform="translate(-1716.000000, -439.000000)"
                      fill="#FFFFFF"
                      fill-rule="nonzero"
                    >
                      <g transform="translate(1716.000000, 291.000000)">
                        <g transform="translate(0.000000, 148.000000)">
                          <path
                            class="color-background opacity-6"
                            d="M46.7199583,10.7414583 L40.8449583,0.949791667 C40.4909749,0.360605034 39.8540131,0 39.1666667,0 L7.83333333,0 C7.1459869,0 6.50902508,0.360605034 6.15504167,0.949791667 L0.280041667,10.7414583 C0.0969176761,11.0460037 -1.23209662e-05,11.3946378 -1.23209662e-05,11.75 C-0.00758042603,16.0663731 3.48367543,19.5725301 7.80004167,19.5833333 L7.81570833,19.5833333 C9.75003686,19.5882688 11.6168794,18.8726691 13.0522917,17.5760417 C16.0171492,20.2556967 20.5292675,20.2556967 23.494125,17.5760417 C26.4604562,20.2616016 30.9794188,20.2616016 33.94575,17.5760417 C36.2421905,19.6477597 39.5441143,20.1708521 42.3684437,18.9103691 C45.1927731,17.649886 47.0084685,14.8428276 47.0000295,11.75 C47.0000295,11.3946378 46.9030823,11.0460037 46.7199583,10.7414583 Z"
                          ></path>
                          <path
                            class="color-background"
                            d="M39.198,22.4912623 C37.3776246,22.4928106 35.5817531,22.0149171 33.951625,21.0951667 L33.92225,21.1107282 C31.1430221,22.6838032 27.9255001,22.9318916 24.9844167,21.7998837 C24.4750389,21.605469 23.9777983,21.3722567 23.4960833,21.1018359 L23.4745417,21.1129513 C20.6961809,22.6871153 17.4786145,22.9344611 14.5386667,21.7998837 C14.029926,21.6054643 13.533337,21.3722507 13.0522917,21.1018359 C11.4250962,22.0190609 9.63246555,22.4947009 7.81570833,22.4912623 C7.16510551,22.4842162 6.51607673,22.4173045 5.875,22.2911849 L5.875,44.7220845 C5.875,45.9498589 6.7517757,46.9451667 7.83333333,46.9451667 L19.5833333,46.9451667 L19.5833333,33.6066734 L27.4166667,33.6066734 L27.4166667,46.9451667 L39.1666667,46.9451667 C40.2482243,46.9451667 41.125,45.9498589 41.125,44.7220845 L41.125,22.2822926 C40.4887822,22.4116582 39.8442868,22.4815492 39.198,22.4912623 Z"
                          ></path>
                        </g>
                      </g>
                    </g>
                  </g>
                </svg>
              </div>
              <span class="nav-link-text ms-1">Dashboard</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <div
                class="icon icon-shape icon-sm shadow border-radius-md bg-white text-center me-2 d-flex align-items-center justify-content-center"
              >
                <i class="fas fa-stop text-dark text-gradient top-0"></i>
              </div>
              <span class="nav-link-text ms-1">Menu 1</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <div
                class="icon icon-shape icon-sm shadow border-radius-md bg-white text-center me-2 d-flex align-items-center justify-content-center"
              >
                <i class="fas fa-stop text-dark text-gradient top-0"></i>
              </div>
              <span class="nav-link-text ms-1">Menu 2</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <div
                class="icon icon-shape icon-sm shadow border-radius-md bg-white text-center me-2 d-flex align-items-center justify-content-center"
              >
                <i class="fas fa-stop text-dark text-gradient top-0"></i>
              </div>
              <span class="nav-link-text ms-1">Menu 3</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <div
                class="icon icon-shape icon-sm shadow border-radius-md bg-white text-center me-2 d-flex align-items-center justify-content-center"
              >
                <i class="fas fa-stop text-dark text-gradient top-0"></i>
              </div>
              <span class="nav-link-text ms-1">Menu 4</span>
            </a>
          </li>
        </ul>
        <div class="mx-3 my-7">
          <div
            class="card card-background shadow-none card-background-mask-secondary"
            id="sidenavCard"
          >
            <div
              class="full-background"
              style="
                background-image: url('../assets/img/curved-images/white-curved.jpeg');
              "
            ></div>
            <div class="card-body text-start p-3 w-100">
              <div class="docs-info">
                <h6 class="text-white up mb-0">Need help?</h6>
                <p class="text-xs font-weight-bold">CoinCap API 2.0</p>
                <a
                  href="https://komgrip.co.th/coincap/"
                  target="_blank"
                  class="btn btn-white btn-sm w-100 mb-0"
                  >Documentation</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </aside>
    <main
      class="main-content position-relative max-height-vh-100 h-100 mt-1 border-radius-lg"
    >
      <!-- Navbar -->
      <nav
        class="navbar navbar-main navbar-expand-lg px-0 mx-4 shadow-none border-radius-xl"
        id="navbarBlur"
        navbar-scroll="true"
      >
        <div class="container-fluid py-1 px-3">
          <nav aria-label="breadcrumb">
            <ol
              class="breadcrumb bg-transparent mb-0 pb-0 pt-1 px-0 me-sm-6 me-5"
            >
              <li class="breadcrumb-item text-sm">
                <a class="opacity-5 text-dark" href="javascript:;">Pages</a>
              </li>
              <li
                class="breadcrumb-item text-sm text-dark active"
                aria-current="page"
              >
                Dashboard
              </li>
            </ol>
            <h6 class="font-weight-bolder mb-0">Dashboard</h6>
          </nav>
          <div
            class="collapse navbar-collapse mt-sm-0 mt-2 me-md-0 me-sm-4"
            id="navbar"
          >
            <div class="ms-md-auto pe-md-3 d-flex align-items-center">
              <div class="input-group">
                <ul class="navbar-nav justify-content-end">
                  <li class="nav-item d-flex align-items-center">
                    <a
                      href="javascript:;"
                      class="nav-link text-body font-weight-bold px-0"
                    >
                      <i class="fa fa-user me-sm-1"></i>
                      <span class="d-sm-inline d-none">Nitikron Piew-on</span>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </nav>
      <!-- End Navbar -->
      <div class="container-fluid py-4">
        <div class="row">
          <div class="col-xl-3 col-sm-6 mb-xl-0 mb-4">
            <div class="card">
              <div class="card-body p-3">
                <div class="row">
                  <div class="col-8">
                    <div class="numbers">
                      <p class="text-sm mb-0 text-capitalize font-weight-bold">
                        Bitcoin
                      </p>
                      <h5 class="font-weight-bolder mb-0">
                        {{ BTC.usd }}
                        <span
                          class="text-danger text-sm font-weight-bolder"
                          v-if="BTC.minusValue"
                          >{{ BTC.percent }}</span
                        >
                        <span
                          class="text-success text-sm font-weight-bolder"
                          v-else
                          >{{ BTC.percent }}</span
                        >
                      </h5>
                    </div>
                  </div>
                  <div class="col-4 text-end">
                    <div
                      class="icon icon-shape bg-gradient-primary shadow text-center border-radius-md"
                    >
                      <i
                        class="ni ni-money-coins text-lg opacity-10"
                        aria-hidden="true"
                      ></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-sm-6 mb-xl-0 mb-4">
            <div class="card">
              <div class="card-body p-3">
                <div class="row">
                  <div class="col-8">
                    <div class="numbers">
                      <p class="text-sm mb-0 text-capitalize font-weight-bold">
                        Ethereum
                      </p>
                      <h5 class="font-weight-bolder mb-0">
                        {{ ETH.usd }}
                        <span
                          class="text-danger text-sm font-weight-bolder"
                          v-if="ETH.minusValue"
                          >{{ ETH.percent }}</span
                        >
                        <span
                          class="text-success text-sm font-weight-bolder"
                          v-else
                          >{{ ETH.percent }}</span
                        >
                      </h5>
                    </div>
                  </div>
                  <div class="col-4 text-end">
                    <div
                      class="icon icon-shape bg-gradient-primary shadow text-center border-radius-md"
                    >
                      <i
                        class="ni ni-money-coins text-lg opacity-10"
                        aria-hidden="true"
                      ></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-sm-6 mb-xl-0 mb-4">
            <div class="card">
              <div class="card-body p-3">
                <div class="row">
                  <div class="col-8">
                    <div class="numbers">
                      <p class="text-sm mb-0 text-capitalize font-weight-bold">
                        Solana
                      </p>
                      <h5 class="font-weight-bolder mb-0">
                        {{ SOL.usd }}
                        <span
                          class="text-danger text-sm font-weight-bolder"
                          v-if="SOL.minusValue"
                          >{{ SOL.percent }}</span
                        >
                        <span
                          class="text-success text-sm font-weight-bolder"
                          v-else
                          >{{ SOL.percent }}</span
                        >
                      </h5>
                    </div>
                  </div>
                  <div class="col-4 text-end">
                    <div
                      class="icon icon-shape bg-gradient-primary shadow text-center border-radius-md"
                    >
                      <i
                        class="ni ni-money-coins text-lg opacity-10"
                        aria-hidden="true"
                      ></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-sm-6">
            <div class="card">
              <div class="card-body p-3">
                <div class="row">
                  <div class="col-8">
                    <div class="numbers">
                      <p class="text-sm mb-0 text-capitalize font-weight-bold">
                        Dogecoin
                      </p>
                      <h5 class="font-weight-bolder mb-0">
                        {{ DOGE.usd }}
                        <span
                          class="text-danger text-sm font-weight-bolder"
                          v-if="DOGE.minusValue"
                          >{{ DOGE.percent }}</span
                        >
                        <span
                          class="text-success text-sm font-weight-bolder"
                          v-else
                          >{{ DOGE.percent }}</span
                        >
                      </h5>
                    </div>
                  </div>
                  <div class="col-4 text-end">
                    <div
                      class="icon icon-shape bg-gradient-primary shadow text-center border-radius-md"
                    >
                      <i
                        class="ni ni-money-coins text-lg opacity-10"
                        aria-hidden="true"
                      ></i>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row my-4">
          <div class="col">
            <div class="card">
              <div class="card-header d-flex justify-content-between">
                <h5>Cryptocurrencies</h5>
                <div>
                  <button
                    class="btn btn-outline-danger mx-2"
                    style="width: 85px"
                    :disabled="beforeRecord < 5"
                    @click="previousPage()"
                  >
                    <i class="fas fa-chevron-left" />
                  </button>
                  <button
                    class="btn btn-outline-danger mx-2"
                    style="width: 85px"
                    :disabled="afterRecord == coinData.length"
                    @click="nextPage()"
                  >
                    <i class="fas fa-chevron-right" />
                  </button>
                </div>
              </div>
              <div class="table-responsive my-2">
                <table class="table align-items-center mb-0">
                  <thead>
                    <tr>
                      <td
                        class="text-center text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        No
                      </td>
                      <td
                        class="text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        Name
                      </td>
                      <td
                        class="text-center text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        Symbol
                      </td>
                      <td
                        class="text-center text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        Supply/ Max Supply
                      </td>
                      <td
                        class="text-center text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        USD
                      </td>
                      <td
                        class="text-center text-uppercase text-secondary text-xs font-weight-bolder opacity-7"
                      >
                        24 HR
                      </td>
                    </tr>
                  </thead>
                  <tbody>
                    <tr
                      style="font-size: small"
                      v-for="item in coinData.slice(beforeRecord, afterRecord)"
                      :key="item.rank"
                    >
                      <td class="text-center">{{ item.rank }}.</td>
                      <td>{{ item.name }}</td>
                      <td class="text-center">{{ item.symbol }}</td>
                      <td class="text-center">
                        {{
                          new Intl.NumberFormat("en-IN").format(
                            Math.round(item.supply)
                          )
                        }}
                        /
                        {{
                          item.maxSupply == null
                            ? "NO LIMIT"
                            : new Intl.NumberFormat("en-IN").format(
                                Math.round(item.maxSupply)
                              )
                        }}
                      </td>
                      <td class="text-center">
                        ${{
                          parseFloat(item.priceUsd) > 999
                            ? new Intl.NumberFormat("en-IN").format(
                                parseFloat(item.priceUsd).toFixed(2)
                              )
                            : parseFloat(item.priceUsd).toFixed(2)
                        }}
                      </td>
                      <td
                        class="text-center text-danger"
                        v-if="parseFloat(item.changePercent24Hr) < 0"
                      >
                        {{ parseFloat(item.changePercent24Hr).toFixed(2) }}%
                      </td>
                      <td class="text-center text-success" v-else>
                        +{{ parseFloat(item.changePercent24Hr).toFixed(2) }}%
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
        <footer class="footer pt-3">
          <div class="container-fluid">
            <div class="row align-items-center justify-content-lg-between">
              <div class="col-lg-6 mb-lg-0 mb-4">
                <div
                  class="copyright text-center text-sm text-muted text-lg-start"
                >
                  Copyright © 2024 Komgrip Technologies Co., Ltd.
                </div>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </main>
  </div>
</template>
<script>
import axios from "axios";
export default {
  name: "DashboardPage",
  data() {
    return {
      coinData: [],
      beforeRecord: 0,
      afterRecord: 5,
      BTC: {
        usd: "-",
        percent: "-",
        minusValue: true,
      },
      ETH: {
        usd: "-",
        percent: "-",
        minusValue: true,
      },
      SOL: {
        usd: "-",
        percent: "-",
        minusValue: true,
      },
      DOGE: {
        usd: "-",
        percent: "-",
        minusValue: true,
      },
    };
  },
  created() {
    this.getCoinData();
  },
  methods: {
    async getCoinData() {
      await axios.get("https://komgrip.co.th/coincap/assets").then((res) => {
        this.coinData = res.data.data;

        let BTC = this.coinData.filter((item) => {
          return item.id == "bitcoin";
        });
        this.BTC.usd =
          "$" +
          new Intl.NumberFormat("en-IN").format(
            parseFloat(BTC[0].priceUsd).toFixed(2)
          );
        this.BTC.percent =
          Math.abs(parseFloat(BTC[0].changePercent24Hr).toFixed(2)) + "%";
        this.BTC.minusValue = parseFloat(BTC[0].changePercent24Hr) < 0;

        let ETH = this.coinData.filter((item) => {
          return item.id == "ethereum";
        });
        this.ETH.usd =
          "$" +
          new Intl.NumberFormat("en-IN").format(
            parseFloat(ETH[0].priceUsd).toFixed(2)
          );
        this.ETH.percent =
          Math.abs(parseFloat(ETH[0].changePercent24Hr).toFixed(2)) + "%";
        this.ETH.minusValue = parseFloat(ETH[0].changePercent24Hr) < 0;

        let SOL = this.coinData.filter((item) => {
          return item.id == "solana";
        });
        this.SOL.usd =
          "$" +
          new Intl.NumberFormat("en-IN").format(
            parseFloat(SOL[0].priceUsd).toFixed(2)
          );
        this.SOL.percent =
          Math.abs(parseFloat(SOL[0].changePercent24Hr).toFixed(2)) + "%";
        this.SOL.minusValue = parseFloat(SOL[0].changePercent24Hr) < 0;

        let DOGE = this.coinData.filter((item) => {
          return item.id == "dogecoin";
        });
        this.DOGE.usd =
          "$" +
          new Intl.NumberFormat("en-IN").format(
            parseFloat(DOGE[0].priceUsd).toFixed(2)
          );
        this.DOGE.percent =
          Math.abs(parseFloat(DOGE[0].changePercent24Hr).toFixed(2)) + "%";
        this.DOGE.minusValue = parseFloat(DOGE[0].changePercent24Hr) < 0;
      });
    },
    nextPage() {
      this.beforeRecord += 5;
      this.afterRecord += 5;
    },
    previousPage() {
      this.beforeRecord -= 5;
      this.afterRecord -= 5;
    },
  },
};
</script>

<style>
button:disabled {
  cursor: not-allowed;
  pointer-events: all !important;
}
</style>
