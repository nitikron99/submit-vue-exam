<template>
  <div>
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
                  :disabled="afterRecord >= coinData.length"
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

      let numberForIncrease;
      if (this.afterRecord + 5 > this.coinData.length) {
        numberForIncrease = this.coinData.length - this.afterRecord;
      } else {
        numberForIncrease = 5;
      }

      this.afterRecord += numberForIncrease;
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
