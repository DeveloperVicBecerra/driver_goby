function _defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if ("value" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } }

function _createClass(Constructor, protoProps, staticProps) { if (protoProps) _defineProperties(Constructor.prototype, protoProps); if (staticProps) _defineProperties(Constructor, staticProps); return Constructor; }

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class as a function"); } }

(window["webpackJsonp"] = window["webpackJsonp"] || []).push([["pages-order-detail-order-detail-module"], {
  /***/
  "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/order-detail/order-detail.page.html":
  /*!*************************************************************************************************!*\
    !*** ./node_modules/raw-loader/dist/cjs.js!./src/app/pages/order-detail/order-detail.page.html ***!
    \*************************************************************************************************/

  /*! exports provided: default */

  /***/
  function node_modulesRawLoaderDistCjsJsSrcAppPagesOrderDetailOrderDetailPageHtml(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony default export */


    __webpack_exports__["default"] = "<ion-header>\n  <ion-toolbar>\n    <ion-buttons slot=\"start\">\n      <ion-button (click)=\"back()\">\n        <ion-icon slot=\"icon-only\" color=\"dark\" mode=\"md\" name=\"arrow-back-outline\"></ion-icon>\n      </ion-button>\n    </ion-buttons>\n    <ion-title>{{'Order Detail' | translate}}</ion-title>\n  </ion-toolbar>\n</ion-header>\n\n<ion-content>\n  <div *ngIf=\"!loaded\" style=\"display: flex;flex-direction: column;justify-content: center;align-items: center;\">\n    <ion-spinner color=\"primary\" name=\"crescent\"></ion-spinner>\n  </div>\n  <div class=\"main_content_div\" *ngIf=\"loaded\">\n\n\n    <div class=\"card_div\">\n      <div class=\"resto_detail\">\n        <div class=\"back_image\" [style.backgroundImage]=\"'url('+usercover+')'\"></div>\n        <div style=\"margin-left: 10px;\">\n          <ion-label class=\"res_name\">{{username}}</ion-label>\n          <ion-label class=\"res_location\">{{time}}</ion-label>\n        </div>\n      </div>\n    </div>\n    <div class=\"orderId\">\n      <div class=\"order_id\">\n        <ion-label>{{'Order ID' | translate}}</ion-label>\n        <ion-label>{{id}}</ion-label>\n      </div>\n    </div>\n    <div class=\"line_div\"></div>\n\n\n    <div class=\"card_div2\" *ngIf=\"userphone\">\n      <div class=\"personal_detail\">\n        <div style=\"display: flex;\">\n          <ion-icon name=\"call\"></ion-icon>&nbsp;&nbsp;\n          <ion-label class=\"res_name\">{{userphone}}</ion-label>\n        </div>\n        <div>\n          <ion-button (click)=\"call()\" size=\"small\" fill=\"outline\">Call</ion-button>\n        </div>\n      </div>\n    </div>\n\n    <div class=\"line_div\"></div>\n\n    <div class=\"card_div2\" *ngIf=\"useremail\">\n      <div class=\"personal_detail\">\n        <div style=\"display: flex;\">\n          <ion-icon name=\"mail\"></ion-icon>&nbsp;&nbsp;\n          <ion-label class=\"res_name\">{{useremail}}</ion-label>\n        </div>\n        <div>\n          <ion-button (click)=\"mail()\" size=\"small\" fill=\"outline\">{{'Email' | translate}}</ion-button>\n        </div>\n      </div>\n    </div>\n\n    <div class=\"line_div\"></div>\n\n    <div class=\"card_div2\">\n      <div class=\"personal_detail\">\n\n        <div style=\"display: flex;\">\n          <ion-icon name=\"location\"></ion-icon>&nbsp;&nbsp;\n          <ion-label class=\"res_name\">{{address}}</ion-label>\n        </div>\n      </div>\n    </div>\n\n    <span>\n      <p style=\"text-align: center;font-size: 14px;font-weight: 600;\">{{'TO' | translate}}</p>\n    </span>\n\n    <div class=\"card_div2\">\n      <div class=\"personal_detail\">\n\n        <div style=\"display: flex;\">\n          <ion-icon name=\"location\"></ion-icon>&nbsp;&nbsp;\n          <ion-label class=\"res_name\">{{deliveryAddress}}</ion-label>\n        </div>\n\n      </div>\n    </div>\n\n    <div class=\"card_div2\">\n      <div class=\"personal_detail\">\n        <div *ngIf=\"status =='ongoing' || status =='created' || status =='picked' || status =='accepted'\">\n          <ion-button (click)=\"goToTracker()\" size=\"small\" fill=\"outline\">{{'Navigate' | translate}}</ion-button>\n        </div>\n      </div>\n    </div>\n    <div class=\"line_div\"></div>\n\n    <div class=\"card_div2\">\n      <div class=\"order_detail\">\n        <ion-label class=\"head_gray\">{{'ITEMS' | translate}}</ion-label>\n        <!-- <div class=\"small_lbl\">\n          <ion-label *ngFor=\"let item of orders\">{{item.quantiy}} X {{item.name}} <span\n              class=\"prize\">{{getCurrency()}}{{item.price}}</span></ion-label>\n        </div> -->\n        <span *ngFor=\"let item of orders\">\n\n          <div *ngFor=\"let subItems of item.selectedItem;let j = index\" class=\"subNames\">\n            <ion-label class=\"food_title\">\n              {{item.name}} X\n              {{item.selectedItem[j].total}}</ion-label>\n            <div *ngFor=\"let addods of subItems.item\" class=\"flex_titles\">\n              <p class=\"sub_name\">\n                - {{addods.name}}\n              </p>\n              <p class=\"sub_name\">\n                {{getCurrency()}} {{addods.value}}\n              </p>\n            </div>\n          </div>\n\n          <div class=\"card_div4\" *ngIf=\"!item.selectedItem || !item.selectedItem.length\">\n            <div class=\"flex_div\">\n              <ion-label class=\"food_title\">{{item.name}} X {{item.quantiy}} </ion-label>\n              <ion-label class=\"food_price\">{{getCurrency()}}{{item.quantiy * item.price}}</ion-label>\n            </div>\n\n          </div>\n\n        </span>\n        <ion-label class=\"head_gray\">{{'ORDERED ON' | translate}}</ion-label>\n        <ion-label class=\"small_lbl\">{{time}} </ion-label>\n      </div>\n    </div>\n\n    <div class=\"line_div\"></div>\n    <div class=\"card_div2\">\n\n      <div class=\"order_detail\">\n        <ion-label class=\"small_lbl2\">{{'SubTotal' | translate}}<span class=\"prize1\">{{getCurrency()}}{{total}}</span>\n        </ion-label>\n        <ion-label class=\"small_lbl2\">{{'Delivery Charge' | translate}}<span class=\"prize1\">{{getCurrency()}}5</span>\n        </ion-label>\n        <ion-label class=\"small_lbl2\">{{'Service Tax' | translate}}<span\n            class=\"prize1\">{{getCurrency()}}{{serviceTax}}</span>\n        </ion-label>\n        <ion-label class=\"small_lbl2\">{{'Total' | translate}}<span class=\"prize1\">{{getCurrency()}}{{grandTotal}}</span>\n        </ion-label>\n\n        <ion-label class=\"small_lbl2\">{{'Way of Payment' | translate}}<span class=\"prize1 red_color\">{{payment}}</span>\n        </ion-label>\n      </div>\n\n    </div>\n  </div>\n</ion-content>\n\n<ion-footer>\n  <ion-toolbar>\n    <!-- <div class=\"btn_div\" *ngIf=\"status == 'created'\">\n      <ion-button (click)=\"picked()\" size=\"small\" class=\"reject\">\n        Picked\n      </ion-button>\n    </div>\n    <div class=\"btn_div\" *ngIf=\"status == 'picked'\">\n      <ion-button (click)=\"delivered()\" size=\"small\" class=\"reject\">\n        Deliver\n      </ion-button>\n    </div> -->\n    <div class=\"status_div\" *ngIf=\"status == 'accepted' || status == 'ongoing' \">\n      <div style=\"width: 200px;\">\n        <ion-select placeholder=\"Choose Status\" [(ngModel)]=\"changeStatusOrder\">\n          <ion-select-option value=\"ongoing\">{{'Ongoing' | translate}}</ion-select-option>\n          <ion-select-option value=\"cancel\">{{'Cancel' | translate}}</ion-select-option>\n          <ion-select-option value=\"delivered\">{{'Delivered' | translate}}</ion-select-option>\n        </ion-select>\n      </div>\n\n      <div>\n        <ion-button (click)=\"changeOrderStatus()\" size=\"small\">\n          {{'Update Status' | translate}}\n        </ion-button>\n      </div>\n    </div>\n    <!-- <ion-label class=\"green\"> Order status : {{status}}</ion-label> -->\n  </ion-toolbar>\n</ion-footer>";
    /***/
  },

  /***/
  "./src/app/pages/order-detail/order-detail-routing.module.ts":
  /*!*******************************************************************!*\
    !*** ./src/app/pages/order-detail/order-detail-routing.module.ts ***!
    \*******************************************************************/

  /*! exports provided: OrderDetailPageRoutingModule */

  /***/
  function srcAppPagesOrderDetailOrderDetailRoutingModuleTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "OrderDetailPageRoutingModule", function () {
      return OrderDetailPageRoutingModule;
    });
    /* harmony import */


    var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! tslib */
    "./node_modules/tslib/tslib.es6.js");
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/fesm2015/core.js");
    /* harmony import */


    var _angular_router__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(
    /*! @angular/router */
    "./node_modules/@angular/router/fesm2015/router.js");
    /* harmony import */


    var _order_detail_page__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(
    /*! ./order-detail.page */
    "./src/app/pages/order-detail/order-detail.page.ts");

    var routes = [{
      path: '',
      component: _order_detail_page__WEBPACK_IMPORTED_MODULE_3__["OrderDetailPage"]
    }];

    var OrderDetailPageRoutingModule = function OrderDetailPageRoutingModule() {
      _classCallCheck(this, OrderDetailPageRoutingModule);
    };

    OrderDetailPageRoutingModule = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
      imports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"].forChild(routes)],
      exports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"]]
    })], OrderDetailPageRoutingModule);
    /***/
  },

  /***/
  "./src/app/pages/order-detail/order-detail.module.ts":
  /*!***********************************************************!*\
    !*** ./src/app/pages/order-detail/order-detail.module.ts ***!
    \***********************************************************/

  /*! exports provided: OrderDetailPageModule */

  /***/
  function srcAppPagesOrderDetailOrderDetailModuleTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "OrderDetailPageModule", function () {
      return OrderDetailPageModule;
    });
    /* harmony import */


    var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! tslib */
    "./node_modules/tslib/tslib.es6.js");
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/fesm2015/core.js");
    /* harmony import */


    var _angular_common__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(
    /*! @angular/common */
    "./node_modules/@angular/common/fesm2015/common.js");
    /* harmony import */


    var _angular_forms__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(
    /*! @angular/forms */
    "./node_modules/@angular/forms/fesm2015/forms.js");
    /* harmony import */


    var _ionic_angular__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(
    /*! @ionic/angular */
    "./node_modules/@ionic/angular/fesm2015/ionic-angular.js");
    /* harmony import */


    var _order_detail_routing_module__WEBPACK_IMPORTED_MODULE_5__ = __webpack_require__(
    /*! ./order-detail-routing.module */
    "./src/app/pages/order-detail/order-detail-routing.module.ts");
    /* harmony import */


    var _order_detail_page__WEBPACK_IMPORTED_MODULE_6__ = __webpack_require__(
    /*! ./order-detail.page */
    "./src/app/pages/order-detail/order-detail.page.ts");
    /* harmony import */


    var src_app_shared_shared_module__WEBPACK_IMPORTED_MODULE_7__ = __webpack_require__(
    /*! src/app/shared/shared.module */
    "./src/app/shared/shared.module.ts");

    var OrderDetailPageModule = function OrderDetailPageModule() {
      _classCallCheck(this, OrderDetailPageModule);
    };

    OrderDetailPageModule = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
      imports: [_angular_common__WEBPACK_IMPORTED_MODULE_2__["CommonModule"], _angular_forms__WEBPACK_IMPORTED_MODULE_3__["FormsModule"], _ionic_angular__WEBPACK_IMPORTED_MODULE_4__["IonicModule"], src_app_shared_shared_module__WEBPACK_IMPORTED_MODULE_7__["SharedModule"], _order_detail_routing_module__WEBPACK_IMPORTED_MODULE_5__["OrderDetailPageRoutingModule"]],
      declarations: [_order_detail_page__WEBPACK_IMPORTED_MODULE_6__["OrderDetailPage"]]
    })], OrderDetailPageModule);
    /***/
  },

  /***/
  "./src/app/pages/order-detail/order-detail.page.scss":
  /*!***********************************************************!*\
    !*** ./src/app/pages/order-detail/order-detail.page.scss ***!
    \***********************************************************/

  /*! exports provided: default */

  /***/
  function srcAppPagesOrderDetailOrderDetailPageScss(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony default export */


    __webpack_exports__["default"] = ".main_content_div {\n  width: 100%;\n}\n.main_content_div .line_div {\n  height: 1px;\n  width: 100%;\n  background: lightgray;\n}\n.main_content_div ion-label {\n  display: block;\n}\n.main_content_div .card_div {\n  padding: 20px;\n}\n.main_content_div .card_div .resto_detail {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-orient: horizontal;\n  -webkit-box-direction: normal;\n          flex-direction: row;\n  -webkit-box-align: center;\n          align-items: center;\n  position: relative;\n}\n.main_content_div .card_div .resto_detail .back_image {\n  height: 50px;\n  width: 50px;\n  background-position: center;\n  background-size: cover;\n  background-repeat: no-repeat;\n  border-radius: 100%;\n}\n.main_content_div .card_div .resto_detail .res_name {\n  font-weight: 600;\n  font-size: 14px;\n}\n.main_content_div .card_div .resto_detail .res_location {\n  color: gray;\n  font-size: 14px;\n}\n.main_content_div .card_div .resto_detail .order_id {\n  position: absolute;\n  right: 5px;\n}\n.main_content_div .card_div .resto_detail .order_id ion-label {\n  text-align: right;\n}\n.main_content_div .orderId {\n  padding: 10px 20px;\n  font-weight: 600;\n  font-size: 14px;\n}\n.main_content_div .card_div2 {\n  padding: 10px 20px;\n}\n.main_content_div .card_div2 .personal_detail {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-orient: vertical;\n  -webkit-box-direction: normal;\n          flex-direction: column;\n  -webkit-box-pack: justify;\n          justify-content: space-between;\n  -webkit-box-align: center;\n          align-items: center;\n}\n.main_content_div .card_div2 .personal_detail ion-icon {\n  font-size: 20px;\n  color: var(--ion-color-primary);\n}\n.main_content_div .card_div2 .personal_detail ion-button {\n  --border-radius: 3px;\n  font-weight: 600;\n}\n.main_content_div .card_div2 .personal_detail .res_name {\n  font-weight: 600;\n  font-size: 14px;\n}\n.main_content_div .card_div2 .order_detail .head_gray {\n  color: gray;\n  font-size: 13px;\n  margin-top: 10px;\n}\n.main_content_div .card_div2 .order_detail .small_lbl {\n  font-size: 14px;\n  font-weight: 600;\n}\n.main_content_div .card_div2 .order_detail .subNames {\n  border-bottom: 1px dashed lightgray;\n  padding-bottom: 10px;\n}\n.main_content_div .card_div2 .order_detail .subNames .food_title {\n  font-size: 15px;\n  font-weight: bold;\n}\n.main_content_div .card_div2 .order_detail .subNames .food_title .veg {\n  height: 12px;\n  width: 12px;\n}\n.main_content_div .card_div2 .order_detail .subNames .food_title .rate_lbl {\n  background: #b2d9b2;\n  border: 1px solid #7bdb7b;\n  padding: 3px 8px;\n  border-radius: 5px;\n  font-size: 14px;\n  font-weight: 600;\n}\n.main_content_div .card_div2 .order_detail .subNames .flex_titles {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-orient: horizontal;\n  -webkit-box-direction: normal;\n          flex-direction: row;\n  -webkit-box-pack: justify;\n          justify-content: space-between;\n}\n.main_content_div .card_div2 .order_detail .subNames .flex_titles .sub_name {\n  margin: 0px;\n  color: black;\n  font-size: 12px;\n}\n.main_content_div .card_div2 .order_detail .prize {\n  position: absolute;\n  right: 35px;\n  font-weight: 600 !important;\n  color: black;\n}\n.main_content_div .card_div2 .order_detail .prize1 {\n  position: absolute;\n  right: 35px;\n  font-weight: 600 !important;\n  color: black;\n  font-size: 16px;\n  text-transform: uppercase;\n}\n.main_content_div .card_div2 .order_detail .red_color {\n  color: var(--ion-color-primary);\n}\n.main_content_div .card_div2 .order_detail .small_lbl2 {\n  font-size: 16px;\n  font-weight: 600;\n  margin-top: 10px;\n}\n.btn_div {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-pack: center;\n          justify-content: center;\n}\n.btn_div ion-button {\n  font-weight: 600;\n  --border-radius: 5px;\n  width: 130px;\n}\n.btn_div .accept {\n  --background: green;\n}\n.status_div {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-pack: justify;\n          justify-content: space-between;\n  padding-left: 20px;\n  padding-right: 20px;\n  -webkit-box-align: center;\n          align-items: center;\n}\n.status_div ion-select {\n  border: 1px solid lightgray;\n  border-radius: 5px;\n  --padding-top: 3px;\n  --padding-bottom:3px;\n  width: 100%;\n}\n.status_div ion-button {\n  font-weight: 600;\n  --border-radius: 5px;\n}\n.green {\n  display: block;\n  text-align: center;\n  color: green;\n  font-weight: 600;\n}\n.red {\n  display: block;\n  text-align: center;\n  color: var(--ion-color-primary);\n  font-weight: 600;\n}\n/*# sourceMappingURL=data:application/json;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbIi9Vc2Vycy9WaWNCZWNlcnJhL0Rvd25sb2Fkcy9pb25pYzVGb29kQXBwRnVsbC9BcHBfY29kZS9Ecml2ZXJBcHAvc3JjL2FwcC9wYWdlcy9vcmRlci1kZXRhaWwvb3JkZXItZGV0YWlsLnBhZ2Uuc2NzcyIsInNyYy9hcHAvcGFnZXMvb3JkZXItZGV0YWlsL29yZGVyLWRldGFpbC5wYWdlLnNjc3MiXSwibmFtZXMiOltdLCJtYXBwaW5ncyI6IkFBQUE7RUFDSSxXQUFBO0FDQ0o7QURDSTtFQUNJLFdBQUE7RUFDQSxXQUFBO0VBQ0EscUJBQUE7QUNDUjtBREVJO0VBQ0ksY0FBQTtBQ0FSO0FER0k7RUFDSSxhQUFBO0FDRFI7QURHUTtFQUNJLG9CQUFBO0VBQUEsYUFBQTtFQUNBLDhCQUFBO0VBQUEsNkJBQUE7VUFBQSxtQkFBQTtFQUNBLHlCQUFBO1VBQUEsbUJBQUE7RUFDQSxrQkFBQTtBQ0RaO0FER1k7RUFDSSxZQUFBO0VBQ0EsV0FBQTtFQUNBLDJCQUFBO0VBQ0Esc0JBQUE7RUFDQSw0QkFBQTtFQUNBLG1CQUFBO0FDRGhCO0FESVk7RUFDRSxnQkFBQTtFQUNBLGVBQUE7QUNGZDtBRElZO0VBQ0ksV0FBQTtFQUNBLGVBQUE7QUNGaEI7QURLWTtFQUNJLGtCQUFBO0VBQ0EsVUFBQTtBQ0hoQjtBRElnQjtFQUNHLGlCQUFBO0FDRm5CO0FET0k7RUFDSSxrQkFBQTtFQUNBLGdCQUFBO0VBQ0EsZUFBQTtBQ0xSO0FEUUk7RUFDSSxrQkFBQTtBQ05SO0FET1E7RUFDSSxvQkFBQTtFQUFBLGFBQUE7RUFDQSw0QkFBQTtFQUFBLDZCQUFBO1VBQUEsc0JBQUE7RUFDQSx5QkFBQTtVQUFBLDhCQUFBO0VBQ0EseUJBQUE7VUFBQSxtQkFBQTtBQ0xaO0FET1k7RUFDSSxlQUFBO0VBQ0EsK0JBQUE7QUNMaEI7QURPWTtFQUNJLG9CQUFBO0VBQ0EsZ0JBQUE7QUNMaEI7QURPWTtFQUNJLGdCQUFBO0VBQ0EsZUFBQTtBQ0xoQjtBRFVZO0VBQ0ksV0FBQTtFQUNBLGVBQUE7RUFDQSxnQkFBQTtBQ1JoQjtBRFVZO0VBQ0ksZUFBQTtFQUNBLGdCQUFBO0FDUmhCO0FEVWE7RUFDRyxtQ0FBQTtFQUNBLG9CQUFBO0FDUmhCO0FEU2dCO0VBQ0ksZUFBQTtFQUNBLGlCQUFBO0FDUHBCO0FEUW9CO0VBQ0ksWUFBQTtFQUNBLFdBQUE7QUNOeEI7QURRb0I7RUFDSSxtQkFBQTtFQUNBLHlCQUFBO0VBQ0EsZ0JBQUE7RUFDQSxrQkFBQTtFQUNBLGVBQUE7RUFDQSxnQkFBQTtBQ054QjtBRFNnQjtFQUNJLG9CQUFBO0VBQUEsYUFBQTtFQUNBLDhCQUFBO0VBQUEsNkJBQUE7VUFBQSxtQkFBQTtFQUNBLHlCQUFBO1VBQUEsOEJBQUE7QUNQcEI7QURRb0I7RUFDSSxXQUFBO0VBQ0EsWUFBQTtFQUNBLGVBQUE7QUNOeEI7QURXWTtFQUNJLGtCQUFBO0VBQ0EsV0FBQTtFQUNBLDJCQUFBO0VBQ0EsWUFBQTtBQ1RoQjtBRFlZO0VBQ0ksa0JBQUE7RUFDQSxXQUFBO0VBQ0EsMkJBQUE7RUFDQSxZQUFBO0VBQ0EsZUFBQTtFQUNBLHlCQUFBO0FDVmhCO0FEY1k7RUFDSSwrQkFBQTtBQ1poQjtBRGVZO0VBQ0ksZUFBQTtFQUNBLGdCQUFBO0VBQ0EsZ0JBQUE7QUNiaEI7QURtQkE7RUFDSSxvQkFBQTtFQUFBLGFBQUE7RUFDQSx3QkFBQTtVQUFBLHVCQUFBO0FDaEJKO0FEa0JJO0VBQ0ksZ0JBQUE7RUFDQSxvQkFBQTtFQUNBLFlBQUE7QUNoQlI7QURrQkk7RUFDSSxtQkFBQTtBQ2hCUjtBRG9CQTtFQUNJLG9CQUFBO0VBQUEsYUFBQTtFQUNBLHlCQUFBO1VBQUEsOEJBQUE7RUFDQSxrQkFBQTtFQUNBLG1CQUFBO0VBQ0EseUJBQUE7VUFBQSxtQkFBQTtBQ2pCSjtBRG1CSTtFQUNJLDJCQUFBO0VBQ0Esa0JBQUE7RUFDQSxrQkFBQTtFQUNBLG9CQUFBO0VBQ0EsV0FBQTtBQ2pCUjtBRG9CSTtFQUNJLGdCQUFBO0VBQ0Esb0JBQUE7QUNsQlI7QURzQkE7RUFDSSxjQUFBO0VBQ0Esa0JBQUE7RUFDQSxZQUFBO0VBQ0EsZ0JBQUE7QUNuQko7QURxQkE7RUFDSSxjQUFBO0VBQ0Esa0JBQUE7RUFDQSwrQkFBQTtFQUNBLGdCQUFBO0FDbEJKIiwiZmlsZSI6InNyYy9hcHAvcGFnZXMvb3JkZXItZGV0YWlsL29yZGVyLWRldGFpbC5wYWdlLnNjc3MiLCJzb3VyY2VzQ29udGVudCI6WyIubWFpbl9jb250ZW50X2RpdntcbiAgICB3aWR0aDogMTAwJTtcblxuICAgIC5saW5lX2RpdntcbiAgICAgICAgaGVpZ2h0OiAxcHg7XG4gICAgICAgIHdpZHRoOiAxMDAlO1xuICAgICAgICBiYWNrZ3JvdW5kOiBsaWdodGdyYXk7XG4gICAgfVxuXG4gICAgaW9uLWxhYmVsIHtcbiAgICAgICAgZGlzcGxheTogYmxvY2s7XG4gICAgfVxuXG4gICAgLmNhcmRfZGl2e1xuICAgICAgICBwYWRkaW5nOiAyMHB4O1xuXG4gICAgICAgIC5yZXN0b19kZXRhaWx7XG4gICAgICAgICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgICAgICAgZmxleC1kaXJlY3Rpb246IHJvdztcbiAgICAgICAgICAgIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gICAgICAgICAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgICAgIFxuICAgICAgICAgICAgLmJhY2tfaW1hZ2V7XG4gICAgICAgICAgICAgICAgaGVpZ2h0OiA1MHB4O1xuICAgICAgICAgICAgICAgIHdpZHRoOiA1MHB4O1xuICAgICAgICAgICAgICAgIGJhY2tncm91bmQtcG9zaXRpb246IGNlbnRlcjtcbiAgICAgICAgICAgICAgICBiYWNrZ3JvdW5kLXNpemU6IGNvdmVyO1xuICAgICAgICAgICAgICAgIGJhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7XG4gICAgICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogMTAwJTtcbiAgICAgICAgICAgIH1cblxuICAgICAgICAgICAgLnJlc19uYW1le1xuICAgICAgICAgICAgICBmb250LXdlaWdodDogNjAwOyAgXG4gICAgICAgICAgICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICAgICAgICAgIH0gXG4gICAgICAgICAgICAucmVzX2xvY2F0aW9ue1xuICAgICAgICAgICAgICAgIGNvbG9yOiBncmF5O1xuICAgICAgICAgICAgICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICAgICAgICAgIH1cblxuICAgICAgICAgICAgLm9yZGVyX2lke1xuICAgICAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgICAgICByaWdodDogNXB4O1xuICAgICAgICAgICAgICAgIGlvbi1sYWJlbCB7XG4gICAgICAgICAgICAgICAgICAgdGV4dC1hbGlnbjogcmlnaHQ7XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgfVxuICAgIC5vcmRlcklke1xuICAgICAgICBwYWRkaW5nOiAxMHB4IDIwcHg7XG4gICAgICAgIGZvbnQtd2VpZ2h0OiA2MDA7ICBcbiAgICAgICAgZm9udC1zaXplOiAxNHB4O1xuICAgIH1cblxuICAgIC5jYXJkX2RpdjJ7XG4gICAgICAgIHBhZGRpbmc6IDEwcHggMjBweDtcbiAgICAgICAgLnBlcnNvbmFsX2RldGFpbHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgICAgICAgICBmbGV4LWRpcmVjdGlvbjogY29sdW1uO1xuICAgICAgICAgICAganVzdGlmeS1jb250ZW50OiBzcGFjZS1iZXR3ZWVuO1xuICAgICAgICAgICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcblxuICAgICAgICAgICAgaW9uLWljb257XG4gICAgICAgICAgICAgICAgZm9udC1zaXplOiAyMHB4O1xuICAgICAgICAgICAgICAgIGNvbG9yOiB2YXIoLS1pb24tY29sb3ItcHJpbWFyeSk7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICBpb24tYnV0dG9uIHtcbiAgICAgICAgICAgICAgICAtLWJvcmRlci1yYWRpdXM6IDNweDtcbiAgICAgICAgICAgICAgICBmb250LXdlaWdodDogNjAwO1xuICAgICAgICAgICAgfVxuICAgICAgICAgICAgLnJlc19uYW1le1xuICAgICAgICAgICAgICAgIGZvbnQtd2VpZ2h0OiA2MDA7ICBcbiAgICAgICAgICAgICAgICBmb250LXNpemU6IDE0cHg7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cblxuICAgICAgICAub3JkZXJfZGV0YWlse1xuICAgICAgICAgICAgLmhlYWRfZ3JheXtcbiAgICAgICAgICAgICAgICBjb2xvcjogZ3JheTtcbiAgICAgICAgICAgICAgICBmb250LXNpemU6IDEzcHg7XG4gICAgICAgICAgICAgICAgbWFyZ2luLXRvcDogMTBweDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgICAgIC5zbWFsbF9sYmx7XG4gICAgICAgICAgICAgICAgZm9udC1zaXplOiAxNHB4O1xuICAgICAgICAgICAgICAgIGZvbnQtd2VpZ2h0OiA2MDA7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAgLnN1Yk5hbWVze1xuICAgICAgICAgICAgICAgIGJvcmRlci1ib3R0b206IDFweCBkYXNoZWQgbGlnaHRncmF5O1xuICAgICAgICAgICAgICAgIHBhZGRpbmctYm90dG9tOiAxMHB4O1xuICAgICAgICAgICAgICAgIC5mb29kX3RpdGxle1xuICAgICAgICAgICAgICAgICAgICBmb250LXNpemU6IDE1cHg7XG4gICAgICAgICAgICAgICAgICAgIGZvbnQtd2VpZ2h0OiBib2xkO1xuICAgICAgICAgICAgICAgICAgICAudmVne1xuICAgICAgICAgICAgICAgICAgICAgICAgaGVpZ2h0OiAxMnB4O1xuICAgICAgICAgICAgICAgICAgICAgICAgd2lkdGg6IDEycHg7XG4gICAgICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgICAgICAgICAgLnJhdGVfbGJse1xuICAgICAgICAgICAgICAgICAgICAgICAgYmFja2dyb3VuZDogI2IyZDliMjtcbiAgICAgICAgICAgICAgICAgICAgICAgIGJvcmRlcjogMXB4IHNvbGlkICM3YmRiN2I7XG4gICAgICAgICAgICAgICAgICAgICAgICBwYWRkaW5nOiAzcHggOHB4O1xuICAgICAgICAgICAgICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogNXB4O1xuICAgICAgICAgICAgICAgICAgICAgICAgZm9udC1zaXplOiAxNHB4O1xuICAgICAgICAgICAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgICAgICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgICAgICAuZmxleF90aXRsZXN7XG4gICAgICAgICAgICAgICAgICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgICAgICAgICAgICAgICAgIGZsZXgtZGlyZWN0aW9uOiByb3c7XG4gICAgICAgICAgICAgICAgICAgIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjtcbiAgICAgICAgICAgICAgICAgICAgLnN1Yl9uYW1le1xuICAgICAgICAgICAgICAgICAgICAgICAgbWFyZ2luOiAwcHg7XG4gICAgICAgICAgICAgICAgICAgICAgICBjb2xvcjogYmxhY2s7XG4gICAgICAgICAgICAgICAgICAgICAgICBmb250LXNpemU6IDEycHg7XG4gICAgICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG5cbiAgICAgICAgICAgIC5wcml6ZXtcbiAgICAgICAgICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgICAgICAgICAgcmlnaHQ6IDM1cHg7XG4gICAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IDYwMCAhaW1wb3J0YW50O1xuICAgICAgICAgICAgICAgIGNvbG9yOiBibGFjaztcbiAgICAgICAgICAgIH1cblxuICAgICAgICAgICAgLnByaXplMXtcbiAgICAgICAgICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgICAgICAgICAgcmlnaHQ6IDM1cHg7XG4gICAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IDYwMCAhaW1wb3J0YW50O1xuICAgICAgICAgICAgICAgIGNvbG9yOiBibGFjaztcbiAgICAgICAgICAgICAgICBmb250LXNpemU6IDE2cHg7XG4gICAgICAgICAgICAgICAgdGV4dC10cmFuc2Zvcm06IHVwcGVyY2FzZTtcbiAgICAgICAgICAgICAgICAvLyBtYXJnaW4tdG9wOiAxMHB4O1xuXG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAucmVkX2NvbG9ye1xuICAgICAgICAgICAgICAgIGNvbG9yOiB2YXIoLS1pb24tY29sb3ItcHJpbWFyeSk7XG4gICAgICAgICAgICB9XG5cbiAgICAgICAgICAgIC5zbWFsbF9sYmwye1xuICAgICAgICAgICAgICAgIGZvbnQtc2l6ZTogMTZweDtcbiAgICAgICAgICAgICAgICBmb250LXdlaWdodDogNjAwO1xuICAgICAgICAgICAgICAgIG1hcmdpbi10b3A6IDEwcHg7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5idG5fZGl2e1xuICAgIGRpc3BsYXk6IGZsZXg7XG4gICAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG5cbiAgICBpb24tYnV0dG9ue1xuICAgICAgICBmb250LXdlaWdodDogNjAwO1xuICAgICAgICAtLWJvcmRlci1yYWRpdXM6IDVweDtcbiAgICAgICAgd2lkdGg6IDEzMHB4O1xuICAgIH1cbiAgICAuYWNjZXB0e1xuICAgICAgICAtLWJhY2tncm91bmQ6IGdyZWVuO1xuICAgIH1cbn1cblxuLnN0YXR1c19kaXZ7XG4gICAgZGlzcGxheTogZmxleDtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG4gICAgcGFkZGluZy1sZWZ0OiAyMHB4O1xuICAgIHBhZGRpbmctcmlnaHQ6IDIwcHg7XG4gICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcblxuICAgIGlvbi1zZWxlY3R7XG4gICAgICAgIGJvcmRlcjogMXB4IHNvbGlkIGxpZ2h0Z3JheTtcbiAgICAgICAgYm9yZGVyLXJhZGl1czogNXB4O1xuICAgICAgICAtLXBhZGRpbmctdG9wOiAzcHg7XG4gICAgICAgIC0tcGFkZGluZy1ib3R0b20gOjNweDtcbiAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgfVxuXG4gICAgaW9uLWJ1dHRvbntcbiAgICAgICAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgICAgICAgLS1ib3JkZXItcmFkaXVzOiA1cHg7XG4gICAgfVxufVxuXG4uZ3JlZW57XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgIGNvbG9yOiBncmVlbjtcbiAgICBmb250LXdlaWdodDogNjAwO1xufVxuLnJlZHtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgY29sb3I6IHZhcigtLWlvbi1jb2xvci1wcmltYXJ5KTtcbiAgICBmb250LXdlaWdodDogNjAwO1xufSIsIi5tYWluX2NvbnRlbnRfZGl2IHtcbiAgd2lkdGg6IDEwMCU7XG59XG4ubWFpbl9jb250ZW50X2RpdiAubGluZV9kaXYge1xuICBoZWlnaHQ6IDFweDtcbiAgd2lkdGg6IDEwMCU7XG4gIGJhY2tncm91bmQ6IGxpZ2h0Z3JheTtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IGlvbi1sYWJlbCB7XG4gIGRpc3BsYXk6IGJsb2NrO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IHtcbiAgcGFkZGluZzogMjBweDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAucmVzdG9fZGV0YWlsIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IHJvdztcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IC5yZXN0b19kZXRhaWwgLmJhY2tfaW1hZ2Uge1xuICBoZWlnaHQ6IDUwcHg7XG4gIHdpZHRoOiA1MHB4O1xuICBiYWNrZ3JvdW5kLXBvc2l0aW9uOiBjZW50ZXI7XG4gIGJhY2tncm91bmQtc2l6ZTogY292ZXI7XG4gIGJhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7XG4gIGJvcmRlci1yYWRpdXM6IDEwMCU7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLnJlc3RvX2RldGFpbCAucmVzX25hbWUge1xuICBmb250LXdlaWdodDogNjAwO1xuICBmb250LXNpemU6IDE0cHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLnJlc3RvX2RldGFpbCAucmVzX2xvY2F0aW9uIHtcbiAgY29sb3I6IGdyYXk7XG4gIGZvbnQtc2l6ZTogMTRweDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAucmVzdG9fZGV0YWlsIC5vcmRlcl9pZCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IDVweDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAucmVzdG9fZGV0YWlsIC5vcmRlcl9pZCBpb24tbGFiZWwge1xuICB0ZXh0LWFsaWduOiByaWdodDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5vcmRlcklkIHtcbiAgcGFkZGluZzogMTBweCAyMHB4O1xuICBmb250LXdlaWdodDogNjAwO1xuICBmb250LXNpemU6IDE0cHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIHtcbiAgcGFkZGluZzogMTBweCAyMHB4O1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2MiAucGVyc29uYWxfZGV0YWlsIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAganVzdGlmeS1jb250ZW50OiBzcGFjZS1iZXR3ZWVuO1xuICBhbGlnbi1pdGVtczogY2VudGVyO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2MiAucGVyc29uYWxfZGV0YWlsIGlvbi1pY29uIHtcbiAgZm9udC1zaXplOiAyMHB4O1xuICBjb2xvcjogdmFyKC0taW9uLWNvbG9yLXByaW1hcnkpO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2MiAucGVyc29uYWxfZGV0YWlsIGlvbi1idXR0b24ge1xuICAtLWJvcmRlci1yYWRpdXM6IDNweDtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdjIgLnBlcnNvbmFsX2RldGFpbCAucmVzX25hbWUge1xuICBmb250LXdlaWdodDogNjAwO1xuICBmb250LXNpemU6IDE0cHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLmhlYWRfZ3JheSB7XG4gIGNvbG9yOiBncmF5O1xuICBmb250LXNpemU6IDEzcHg7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnNtYWxsX2xibCB7XG4gIGZvbnQtc2l6ZTogMTRweDtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdjIgLm9yZGVyX2RldGFpbCAuc3ViTmFtZXMge1xuICBib3JkZXItYm90dG9tOiAxcHggZGFzaGVkIGxpZ2h0Z3JheTtcbiAgcGFkZGluZy1ib3R0b206IDEwcHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnN1Yk5hbWVzIC5mb29kX3RpdGxlIHtcbiAgZm9udC1zaXplOiAxNXB4O1xuICBmb250LXdlaWdodDogYm9sZDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdjIgLm9yZGVyX2RldGFpbCAuc3ViTmFtZXMgLmZvb2RfdGl0bGUgLnZlZyB7XG4gIGhlaWdodDogMTJweDtcbiAgd2lkdGg6IDEycHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnN1Yk5hbWVzIC5mb29kX3RpdGxlIC5yYXRlX2xibCB7XG4gIGJhY2tncm91bmQ6ICNiMmQ5YjI7XG4gIGJvcmRlcjogMXB4IHNvbGlkICM3YmRiN2I7XG4gIHBhZGRpbmc6IDNweCA4cHg7XG4gIGJvcmRlci1yYWRpdXM6IDVweDtcbiAgZm9udC1zaXplOiAxNHB4O1xuICBmb250LXdlaWdodDogNjAwO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2MiAub3JkZXJfZGV0YWlsIC5zdWJOYW1lcyAuZmxleF90aXRsZXMge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogcm93O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnN1Yk5hbWVzIC5mbGV4X3RpdGxlcyAuc3ViX25hbWUge1xuICBtYXJnaW46IDBweDtcbiAgY29sb3I6IGJsYWNrO1xuICBmb250LXNpemU6IDEycHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnByaXplIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICByaWdodDogMzVweDtcbiAgZm9udC13ZWlnaHQ6IDYwMCAhaW1wb3J0YW50O1xuICBjb2xvcjogYmxhY2s7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnByaXplMSB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IDM1cHg7XG4gIGZvbnQtd2VpZ2h0OiA2MDAgIWltcG9ydGFudDtcbiAgY29sb3I6IGJsYWNrO1xuICBmb250LXNpemU6IDE2cHg7XG4gIHRleHQtdHJhbnNmb3JtOiB1cHBlcmNhc2U7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnJlZF9jb2xvciB7XG4gIGNvbG9yOiB2YXIoLS1pb24tY29sb3ItcHJpbWFyeSk7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYyIC5vcmRlcl9kZXRhaWwgLnNtYWxsX2xibDIge1xuICBmb250LXNpemU6IDE2cHg7XG4gIGZvbnQtd2VpZ2h0OiA2MDA7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG59XG5cbi5idG5fZGl2IHtcbiAgZGlzcGxheTogZmxleDtcbiAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG59XG4uYnRuX2RpdiBpb24tYnV0dG9uIHtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgLS1ib3JkZXItcmFkaXVzOiA1cHg7XG4gIHdpZHRoOiAxMzBweDtcbn1cbi5idG5fZGl2IC5hY2NlcHQge1xuICAtLWJhY2tncm91bmQ6IGdyZWVuO1xufVxuXG4uc3RhdHVzX2RpdiB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjtcbiAgcGFkZGluZy1sZWZ0OiAyMHB4O1xuICBwYWRkaW5nLXJpZ2h0OiAyMHB4O1xuICBhbGlnbi1pdGVtczogY2VudGVyO1xufVxuLnN0YXR1c19kaXYgaW9uLXNlbGVjdCB7XG4gIGJvcmRlcjogMXB4IHNvbGlkIGxpZ2h0Z3JheTtcbiAgYm9yZGVyLXJhZGl1czogNXB4O1xuICAtLXBhZGRpbmctdG9wOiAzcHg7XG4gIC0tcGFkZGluZy1ib3R0b206M3B4O1xuICB3aWR0aDogMTAwJTtcbn1cbi5zdGF0dXNfZGl2IGlvbi1idXR0b24ge1xuICBmb250LXdlaWdodDogNjAwO1xuICAtLWJvcmRlci1yYWRpdXM6IDVweDtcbn1cblxuLmdyZWVuIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgY29sb3I6IGdyZWVuO1xuICBmb250LXdlaWdodDogNjAwO1xufVxuXG4ucmVkIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgY29sb3I6IHZhcigtLWlvbi1jb2xvci1wcmltYXJ5KTtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbn0iXX0= */";
    /***/
  },

  /***/
  "./src/app/pages/order-detail/order-detail.page.ts":
  /*!*********************************************************!*\
    !*** ./src/app/pages/order-detail/order-detail.page.ts ***!
    \*********************************************************/

  /*! exports provided: OrderDetailPage */

  /***/
  function srcAppPagesOrderDetailOrderDetailPageTs(module, __webpack_exports__, __webpack_require__) {
    "use strict";

    __webpack_require__.r(__webpack_exports__);
    /* harmony export (binding) */


    __webpack_require__.d(__webpack_exports__, "OrderDetailPage", function () {
      return OrderDetailPage;
    });
    /* harmony import */


    var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(
    /*! tslib */
    "./node_modules/tslib/tslib.es6.js");
    /* harmony import */


    var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(
    /*! @angular/core */
    "./node_modules/@angular/core/fesm2015/core.js");
    /* harmony import */


    var _angular_router__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(
    /*! @angular/router */
    "./node_modules/@angular/router/fesm2015/router.js");
    /* harmony import */


    var src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(
    /*! src/app/services/api.service */
    "./src/app/services/api.service.ts");
    /* harmony import */


    var src_app_services_util_service__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(
    /*! src/app/services/util.service */
    "./src/app/services/util.service.ts");
    /* harmony import */


    var _ionic_angular__WEBPACK_IMPORTED_MODULE_5__ = __webpack_require__(
    /*! @ionic/angular */
    "./node_modules/@ionic/angular/fesm2015/ionic-angular.js");
    /* harmony import */


    var sweetalert2__WEBPACK_IMPORTED_MODULE_6__ = __webpack_require__(
    /*! sweetalert2 */
    "./node_modules/sweetalert2/dist/sweetalert2.all.js");
    /* harmony import */


    var sweetalert2__WEBPACK_IMPORTED_MODULE_6___default = /*#__PURE__*/__webpack_require__.n(sweetalert2__WEBPACK_IMPORTED_MODULE_6__);

    var OrderDetailPage = /*#__PURE__*/function () {
      function OrderDetailPage(route, api, router, util, navCtrl) {
        _classCallCheck(this, OrderDetailPage);

        this.route = route;
        this.api = api;
        this.router = router;
        this.util = util;
        this.navCtrl = navCtrl;
        this.orders = [];
        this.loaded = false;
      }

      _createClass(OrderDetailPage, [{
        key: "ngOnInit",
        value: function ngOnInit() {
          var _this = this;

          this.route.queryParams.subscribe(function (data) {
            console.log(data);
            _this.tab_id = data.id;
            _this.id = data.id;

            _this.getOrder();
          });
        }
      }, {
        key: "getOrder",
        value: function getOrder() {
          var _this2 = this;

          // this.util.show();
          this.api.getOrderById(this.id).then(function (data) {
            // this.util.hide();
            _this2.loaded = true;
            console.log(data);

            if (data) {
              _this2.grandTotal = data.grandTotal;
              _this2.orders = JSON.parse(data.order);
              _this2.serviceTax = data.serviceTax;
              _this2.status = data.status;
              _this2.time = data.time;
              _this2.total = data.total;
              _this2.address = data.vid.address;
              _this2.restName = data.vid.name;
              _this2.deliveryAddress = data.address.address;
              _this2.username = data.uid.fullname;
              _this2.useremail = data.uid.email;
              _this2.userphone = data.uid.phone;
              _this2.usercover = data.uid && data.uid.cover ? data.uid.cover : 'assets/imgs/user.jpg';
              ;
              _this2.payment = data.paid;
              _this2.myname = data.dId.fullname;
              _this2.token = data.uid.fcm_token;
              console.log('this', _this2.orders);
            }
          }, function (error) {
            console.log('error in orders', error); // this.util.hide();

            _this2.loaded = true;

            _this2.util.errorToast(_this2.util.translate('Something went wrong'));
          }).catch(function (error) {
            console.log('error in order', error); // this.util.hide();

            _this2.loaded = true;

            _this2.util.errorToast(_this2.util.translate('Something went wrong'));
          });
        }
      }, {
        key: "changeStatus",
        value: function changeStatus(value) {
          var _this3 = this;

          this.util.show();
          this.api.updateOrderStatus(this.id, value).then(function (data) {
            console.log('data', data);

            var msg = _this3.util.translate('Your Order is ') + value + _this3.util.translate(' By ') + _this3.restName;

            if (value === 'delivered' || value === 'cancel') {
              var parm = {
                current: 'active'
              };

              _this3.api.updateProfile(localStorage.getItem('uid'), parm).then(function (data) {
                console.log('driver status cahcnage----->', data);
              }).catch(function (error) {
                console.log(error);
              });
            }

            _this3.api.sendNotification(msg, 'Order ' + value, _this3.token).subscribe(function (data) {
              console.log(data);

              _this3.util.hide();
            }, function (error) {
              _this3.util.hide();

              console.log('err', error);
            });

            _this3.util.publishNewAddress('hello');

            sweetalert2__WEBPACK_IMPORTED_MODULE_6___default.a.fire({
              title: _this3.util.translate('success'),
              text: _this3.util.translate('Order status changed to ') + value,
              icon: 'success',
              timer: 2000,
              backdrop: false,
              background: 'white'
            });

            _this3.navCtrl.navigateRoot(['/tabs/tab1']);
          }).catch(function (error) {
            console.log(error);

            _this3.util.hide();

            _this3.navCtrl.navigateRoot(['/tabs/tab1']);

            _this3.util.errorToast(_this3.util.translate('Something went wrong'));
          });
        }
      }, {
        key: "changeOrderStatus",
        value: function changeOrderStatus() {
          console.log('order status', this.changeStatusOrder);

          if (this.changeStatusOrder) {
            this.changeStatus(this.changeStatusOrder);
          }
        }
      }, {
        key: "goToTracker",
        value: function goToTracker() {
          var navData = {
            queryParams: {
              id: this.id
            }
          };
          this.router.navigate(['/tracker'], navData);
        }
      }, {
        key: "call",
        value: function call() {
          window.open('https://api.whatsapp.com/send?phone=91' + this.userphone);
        }
      }, {
        key: "mail",
        value: function mail() {
          window.open('mailto:' + this.useremail);
        }
      }, {
        key: "back",
        value: function back() {
          this.util.publishNewAddress('hello');
          this.navCtrl.back();
        }
      }, {
        key: "picked",
        value: function picked() {
          var _this4 = this;

          this.util.show();
          this.api.updateOrderStatus(this.id, 'ongoing').then(function (data) {
            console.log(data);

            _this4.util.hide();

            var msg = _this4.myname + _this4.util.translate(' Picked up your order');

            _this4.api.sendNotification(msg, _this4.util.translate('Order Picked'), _this4.token).subscribe(function (data) {
              console.log(data);
            });

            _this4.navCtrl.back();

            _this4.util.publishNewAddress('hello');

            sweetalert2__WEBPACK_IMPORTED_MODULE_6___default.a.fire({
              title: 'success',
              text: _this4.util.translate('Order status changed to ') + 'ongoing',
              icon: 'success',
              timer: 2000,
              backdrop: false,
              background: 'white'
            });

            _this4.navCtrl.back();
          }, function (error) {
            _this4.util.hide();

            console.log('error', error);
          }).catch(function (error) {
            console.log(error);

            _this4.util.hide();
          });
        }
      }, {
        key: "getCurrency",
        value: function getCurrency() {
          return this.util.getCurrecySymbol();
        }
      }, {
        key: "delivered",
        value: function delivered() {
          var _this5 = this;

          this.util.show();
          this.api.updateOrderStatus(this.id, 'delivered').then(function (data) {
            console.log(data);

            _this5.util.hide();

            var msg = _this5.myname + _this5.util.translate(' Delivered your order');

            var parm = {
              current: 'active'
            };

            _this5.api.updateProfile(localStorage.getItem('uid'), parm).then(function (data) {
              console.log('driver status cahcnage----->', data);
            }).catch(function (error) {
              console.log(error);
            });

            _this5.api.sendNotification(msg, _this5.util.translate('Order delivered'), _this5.token).subscribe(function (data) {
              console.log(data);
            });

            _this5.navCtrl.back();
          }, function (error) {
            _this5.util.hide();

            console.log('error', error);

            _this5.util.errorToast(_this5.util.translate('Something went wrong'));
          }).catch(function (error) {
            console.log(error);

            _this5.util.hide();

            _this5.util.errorToast(_this5.util.translate('Something went wrong'));
          });
        }
      }]);

      return OrderDetailPage;
    }();

    OrderDetailPage.ctorParameters = function () {
      return [{
        type: _angular_router__WEBPACK_IMPORTED_MODULE_2__["ActivatedRoute"]
      }, {
        type: src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__["ApiService"]
      }, {
        type: _angular_router__WEBPACK_IMPORTED_MODULE_2__["Router"]
      }, {
        type: src_app_services_util_service__WEBPACK_IMPORTED_MODULE_4__["UtilService"]
      }, {
        type: _ionic_angular__WEBPACK_IMPORTED_MODULE_5__["NavController"]
      }];
    };

    OrderDetailPage = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["Component"])({
      selector: 'app-order-detail',
      template: tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"](__webpack_require__(
      /*! raw-loader!./order-detail.page.html */
      "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/order-detail/order-detail.page.html")).default,
      styles: [tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"](__webpack_require__(
      /*! ./order-detail.page.scss */
      "./src/app/pages/order-detail/order-detail.page.scss")).default]
    }), tslib__WEBPACK_IMPORTED_MODULE_0__["__metadata"]("design:paramtypes", [_angular_router__WEBPACK_IMPORTED_MODULE_2__["ActivatedRoute"], src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__["ApiService"], _angular_router__WEBPACK_IMPORTED_MODULE_2__["Router"], src_app_services_util_service__WEBPACK_IMPORTED_MODULE_4__["UtilService"], _ionic_angular__WEBPACK_IMPORTED_MODULE_5__["NavController"]])], OrderDetailPage);
    /***/
  }
}]);
//# sourceMappingURL=pages-order-detail-order-detail-module-es5.js.map