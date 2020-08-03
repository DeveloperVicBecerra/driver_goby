(window["webpackJsonp"] = window["webpackJsonp"] || []).push([["default~orders-orders-module~pages-orders-orders-module"],{

/***/ "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/orders/orders.page.html":
/*!*************************************************************************************!*\
  !*** ./node_modules/raw-loader/dist/cjs.js!./src/app/pages/orders/orders.page.html ***!
  \*************************************************************************************/
/*! exports provided: default */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony default export */ __webpack_exports__["default"] = ("<ion-header>\n  <ion-toolbar>\n    <ion-title>{{'Orders' | translate}}</ion-title>\n  </ion-toolbar>\n  <div class=\"segment_div\">\n    <ion-label [class.active]=\"seg_id == 1\" (click)=\"onClick(1)\">{{'Current Orders' | translate}}</ion-label>\n    <ion-label [class.active]=\"seg_id == 2\" (click)=\"onClick(2)\">{{'Past Orders' | translate}}</ion-label>\n  </div>\n</ion-header>\n\n<ion-content>\n  <div class=\"main_content_div\">\n\n    <div class=\"centent_div\" *ngIf=\"seg_id == 1\">\n      <h2 class=\"ion-text-center\" *ngIf=\"!dummy?.length && !orders?.length\">{{'No Order' | translate}}</h2>\n\n      <ion-item *ngFor=\"let item of dummy\">\n        <ion-thumbnail>\n          <ion-skeleton-text animated></ion-skeleton-text>\n        </ion-thumbnail>\n        <ion-label>\n          <h3>\n            <ion-skeleton-text animated style=\"width: 50%\"></ion-skeleton-text>\n          </h3>\n          <p>\n            <ion-skeleton-text animated style=\"width: 80%\"></ion-skeleton-text>\n          </p>\n          <p>\n            <ion-skeleton-text animated style=\"width: 60%\"></ion-skeleton-text>\n          </p>\n        </ion-label>\n      </ion-item>\n      <div class=\"card_div\" *ngFor=\"let item of orders\" (click)=\"goToOrderDetail(item.id)\">\n\n        <div class=\"resto_detail\">\n          <div class=\"back_image\" [style.backgroundImage]=\"'url('+getProfilePic(item.uid)+')'\"></div>\n          <div style=\"margin-left: 10px;\">\n            <ion-label class=\"res_name\">{{item.uid.fullname}}</ion-label>\n            <ion-label class=\"res_location\">{{item.time}}</ion-label>\n          </div>\n\n          <div class=\"order_id\">\n            <ion-label>{{'Order ID' |  translate}}</ion-label>\n            <ion-label>{{item.id}}</ion-label>\n          </div>\n        </div>\n\n        <div class=\"line_div\"></div>\n\n        <div class=\"order_detail\">\n          <ion-label class=\"head_gray\">{{'ITEMS' | translate}}</ion-label>\n          <!-- <div class=\"small_lbl\">\n            <ion-label *ngFor=\"let order of item.order\">{{order.quantiy}} X {{order.name}} <span\n                class=\"prize\">{{getCurrency()}}{{order.price}}</span></ion-label>\n          </div> -->\n          <div class=\"small_lbl\">\n            <span *ngFor=\"let order of item.order;let ol = index\">\n              <div *ngIf=\"!order.selectedItem || !order.selectedItem.length\" class=\"border_bottom\">\n                {{order.name}} X {{order.quantiy}} <span *ngIf=\"ol !=item.order.length\">,</span>\n              </div>\n\n              <div *ngFor=\"let subItems of order.selectedItem;let j = index\" class=\"subNames\">\n                <ion-label class=\"food_title\">{{order.name}} X {{order.selectedItem[j].total}}</ion-label>\n                <div *ngFor=\"let addods of subItems.item\" class=\"flex_titles\">\n                  <p class=\"sub_name\">\n                    - {{addods.name}}\n                  </p>\n                  <p class=\"sub_name\">\n                    {{getCurrency()}} {{addods.value}}\n                  </p>\n                </div>\n              </div>\n            </span>\n          </div>\n          <ion-label class=\"head_gray\">{{'ORDERED ON' | translate}}</ion-label>\n          <ion-label class=\"small_lbl\">{{item.time}} </ion-label>\n          <ion-label class=\"head_gray\">{{'TOTAL AMOUNT' | translate}}</ion-label>\n          <ion-label class=\"small_lbl\">{{getCurrency()}}{{item.grandTotal}}</ion-label>\n\n          <ion-label class=\"payment_status\">{{item.paid}}</ion-label>\n        </div>\n\n      </div>\n    </div>\n\n    <div class=\"centent_div\" *ngIf=\"seg_id == 2\">\n      <h2 class=\"ion-text-center\" *ngIf=\"!dummy?.length && !oldOrders?.length\">{{'No Order' | translate}}</h2>\n      <ion-item *ngFor=\"let item of dummy\">\n        <ion-thumbnail>\n          <ion-skeleton-text animated></ion-skeleton-text>\n        </ion-thumbnail>\n        <ion-label>\n          <h3>\n            <ion-skeleton-text animated style=\"width: 50%\"></ion-skeleton-text>\n          </h3>\n          <p>\n            <ion-skeleton-text animated style=\"width: 80%\"></ion-skeleton-text>\n          </p>\n          <p>\n            <ion-skeleton-text animated style=\"width: 60%\"></ion-skeleton-text>\n          </p>\n        </ion-label>\n      </ion-item>\n      <div class=\"card_div\" *ngFor=\"let item of oldOrders\" (click)=\"goToOrderDetail(item.id)\">\n\n        <div class=\"resto_detail\">\n          <div class=\"back_image\" [style.backgroundImage]=\"'url('+getProfilePic(item.uid)+')'\"></div>\n          <div style=\"margin-left: 10px;\">\n            <ion-label class=\"res_name\">{{item.uid.fullname}}</ion-label>\n            <ion-label class=\"res_location\">{{item.time}}</ion-label>\n          </div>\n\n          <div class=\"order_id\">\n            <ion-label>{{'Order ID' | translate}}</ion-label>\n            <ion-label>{{item.id}}</ion-label>\n          </div>\n        </div>\n\n        <div class=\"line_div\"></div>\n\n        <div class=\"order_detail\">\n          <ion-label class=\"head_gray\">{{'ITEMS' | translate}}</ion-label>\n          <!-- <div class=\"small_lbl\">\n            <ion-label *ngFor=\"let order of item.order\">{{order.quantiy}} X {{order.name}} <span\n                class=\"prize\">{{getCurrency()}}{{order.price}}</span></ion-label>\n          </div> -->\n          <div class=\"small_lbl\">\n            <span *ngFor=\"let order of item.order;let ol = index\">\n              <div *ngIf=\"!order.selectedItem || !order.selectedItem.length\" class=\"border_bottom\">\n                {{order.name}} X {{order.quantiy}} <span *ngIf=\"ol !=item.order.length\">,</span>\n              </div>\n\n              <div *ngFor=\"let subItems of order.selectedItem;let j = index\" class=\"subNames\">\n                <ion-label class=\"food_title\">{{order.name}} X {{order.selectedItem[j].total}}</ion-label>\n                <div *ngFor=\"let addods of subItems.item\" class=\"flex_titles\">\n                  <p class=\"sub_name\">\n                    - {{addods.name}}\n                  </p>\n                  <p class=\"sub_name\">\n                    {{getCurrency()}} {{addods.value}}\n                  </p>\n                </div>\n              </div>\n            </span>\n          </div>\n          <ion-label class=\"head_gray\">{{'ORDERED ON' | translate}}</ion-label>\n          <ion-label class=\"small_lbl\">{{item.time}} </ion-label>\n          <ion-label class=\"head_gray\">{{'TOTAL AMOUNT' | translate}}</ion-label>\n          <ion-label class=\"small_lbl\">{{getCurrency()}}{{item.grandTotal}}</ion-label>\n\n          <ion-label class=\"payment_status\">{{item.status}}</ion-label>\n        </div>\n\n      </div>\n    </div>\n  </div>\n</ion-content>");

/***/ }),

/***/ "./src/app/pages/orders/orders-routing.module.ts":
/*!*******************************************************!*\
  !*** ./src/app/pages/orders/orders-routing.module.ts ***!
  \*******************************************************/
/*! exports provided: OrdersPageRoutingModule */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "OrdersPageRoutingModule", function() { return OrdersPageRoutingModule; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/fesm2015/core.js");
/* harmony import */ var _angular_router__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @angular/router */ "./node_modules/@angular/router/fesm2015/router.js");
/* harmony import */ var _orders_page__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! ./orders.page */ "./src/app/pages/orders/orders.page.ts");




const routes = [
    {
        path: '',
        component: _orders_page__WEBPACK_IMPORTED_MODULE_3__["OrdersPage"]
    }
];
let OrdersPageRoutingModule = class OrdersPageRoutingModule {
};
OrdersPageRoutingModule = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
        imports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"].forChild(routes)],
        exports: [_angular_router__WEBPACK_IMPORTED_MODULE_2__["RouterModule"]],
    })
], OrdersPageRoutingModule);



/***/ }),

/***/ "./src/app/pages/orders/orders.module.ts":
/*!***********************************************!*\
  !*** ./src/app/pages/orders/orders.module.ts ***!
  \***********************************************/
/*! exports provided: OrdersPageModule */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "OrdersPageModule", function() { return OrdersPageModule; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/fesm2015/core.js");
/* harmony import */ var _angular_common__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @angular/common */ "./node_modules/@angular/common/fesm2015/common.js");
/* harmony import */ var _angular_forms__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! @angular/forms */ "./node_modules/@angular/forms/fesm2015/forms.js");
/* harmony import */ var _ionic_angular__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(/*! @ionic/angular */ "./node_modules/@ionic/angular/fesm2015/ionic-angular.js");
/* harmony import */ var _orders_routing_module__WEBPACK_IMPORTED_MODULE_5__ = __webpack_require__(/*! ./orders-routing.module */ "./src/app/pages/orders/orders-routing.module.ts");
/* harmony import */ var _orders_page__WEBPACK_IMPORTED_MODULE_6__ = __webpack_require__(/*! ./orders.page */ "./src/app/pages/orders/orders.page.ts");
/* harmony import */ var src_app_shared_shared_module__WEBPACK_IMPORTED_MODULE_7__ = __webpack_require__(/*! src/app/shared/shared.module */ "./src/app/shared/shared.module.ts");








let OrdersPageModule = class OrdersPageModule {
};
OrdersPageModule = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["NgModule"])({
        imports: [
            _angular_common__WEBPACK_IMPORTED_MODULE_2__["CommonModule"],
            _angular_forms__WEBPACK_IMPORTED_MODULE_3__["FormsModule"],
            _ionic_angular__WEBPACK_IMPORTED_MODULE_4__["IonicModule"],
            src_app_shared_shared_module__WEBPACK_IMPORTED_MODULE_7__["SharedModule"],
            _orders_routing_module__WEBPACK_IMPORTED_MODULE_5__["OrdersPageRoutingModule"]
        ],
        declarations: [_orders_page__WEBPACK_IMPORTED_MODULE_6__["OrdersPage"]]
    })
], OrdersPageModule);



/***/ }),

/***/ "./src/app/pages/orders/orders.page.scss":
/*!***********************************************!*\
  !*** ./src/app/pages/orders/orders.page.scss ***!
  \***********************************************/
/*! exports provided: default */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony default export */ __webpack_exports__["default"] = (".segment_div {\n  display: -webkit-box;\n  display: flex;\n  margin-top: 20px;\n  border-bottom: 1px solid lightgray;\n  justify-content: space-around;\n}\n.segment_div ion-label {\n  color: gray;\n  padding-bottom: 10px;\n  width: 100%;\n  text-align: center;\n}\n.segment_div .active {\n  border-bottom: 1px solid red;\n}\n.main_content_div {\n  width: 100%;\n}\n.main_content_div .centent_div {\n  padding: 20px;\n}\n.main_content_div .centent_div ion-label {\n  display: block;\n}\n.main_content_div .card_div {\n  width: 100%;\n  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.2);\n  border-radius: 10px;\n  padding: 15px;\n  margin-bottom: 20px;\n  border: 0.5px solid lightgray;\n}\n.main_content_div .card_div .line_div {\n  height: 1px;\n  width: 100%;\n  background: lightgray;\n  margin-top: 10px;\n  margin-bottom: 10px;\n}\n.main_content_div .card_div .resto_detail {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-orient: horizontal;\n  -webkit-box-direction: normal;\n          flex-direction: row;\n  -webkit-box-align: center;\n          align-items: center;\n  position: relative;\n}\n.main_content_div .card_div .resto_detail .back_image {\n  height: 50px;\n  width: 50px;\n  background-position: center;\n  background-size: cover;\n  background-repeat: no-repeat;\n  border-radius: 100%;\n}\n.main_content_div .card_div .resto_detail .res_name {\n  font-weight: 600;\n  font-size: 14px;\n}\n.main_content_div .card_div .resto_detail .res_location {\n  color: lightgray;\n  font-size: 14px;\n}\n.main_content_div .card_div .resto_detail .order_id {\n  position: absolute;\n  right: 5px;\n  font-size: 0.6rem;\n}\n.main_content_div .card_div .resto_detail .order_id ion-label {\n  text-align: right;\n}\n.main_content_div .card_div .order_detail {\n  position: relative;\n}\n.main_content_div .card_div .order_detail .head_gray {\n  color: lightgray;\n  font-size: 13px;\n  margin-top: 10px;\n}\n.main_content_div .card_div .order_detail .small_lbl {\n  font-size: 14px;\n  font-weight: 600;\n}\n.main_content_div .card_div .order_detail .border_bottom {\n  border-bottom: 1px dashed lightgray;\n  padding: 5px 0px;\n  font-size: 15px;\n  font-weight: bold;\n}\n.main_content_div .card_div .order_detail .subNames {\n  border-bottom: 1px dashed lightgray;\n  padding-bottom: 5px;\n}\n.main_content_div .card_div .order_detail .subNames .food_title {\n  font-size: 15px;\n  font-weight: bold;\n}\n.main_content_div .card_div .order_detail .subNames .flex_titles {\n  display: -webkit-box;\n  display: flex;\n  -webkit-box-orient: horizontal;\n  -webkit-box-direction: normal;\n          flex-direction: row;\n  -webkit-box-pack: justify;\n          justify-content: space-between;\n}\n.main_content_div .card_div .order_detail .subNames .flex_titles .sub_name {\n  margin: 0px;\n  color: black;\n  font-size: 12px;\n}\n.main_content_div .card_div .order_detail .prize {\n  position: absolute;\n  right: 35px;\n  font-weight: 600 !important;\n}\n.main_content_div .card_div .order_detail .payment_status {\n  position: absolute;\n  right: -15px;\n  text-transform: uppercase;\n  bottom: -15px;\n  background: var(--ion-color-primary);\n  color: white;\n  font-weight: 600;\n  padding: 8px 12px;\n  border-bottom-right-radius: 10px;\n}\n/*# sourceMappingURL=data:application/json;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbIi9Vc2Vycy9WaWNCZWNlcnJhL0Rvd25sb2Fkcy9pb25pYzVGb29kQXBwRnVsbC9BcHBfY29kZS9Ecml2ZXJBcHAvc3JjL2FwcC9wYWdlcy9vcmRlcnMvb3JkZXJzLnBhZ2Uuc2NzcyIsInNyYy9hcHAvcGFnZXMvb3JkZXJzL29yZGVycy5wYWdlLnNjc3MiXSwibmFtZXMiOltdLCJtYXBwaW5ncyI6IkFBQUM7RUFDTyxvQkFBQTtFQUFBLGFBQUE7RUFDQSxnQkFBQTtFQUNBLGtDQUFBO0VBQ0EsNkJBQUE7QUNDUjtBREFRO0VBQ0ksV0FBQTtFQUNBLG9CQUFBO0VBQ0EsV0FBQTtFQUNBLGtCQUFBO0FDRVo7QURBUTtFQUNJLDRCQUFBO0FDRVo7QURDQTtFQUNJLFdBQUE7QUNFSjtBRERJO0VBQ0ksYUFBQTtBQ0dSO0FERFE7RUFDSSxjQUFBO0FDR1o7QURDSTtFQUNJLFdBQUE7RUFDQSwwQ0FBQTtFQUNBLG1CQUFBO0VBQ0EsYUFBQTtFQUNBLG1CQUFBO0VBQ0EsNkJBQUE7QUNDUjtBRENRO0VBQ0ksV0FBQTtFQUNBLFdBQUE7RUFDQSxxQkFBQTtFQUNBLGdCQUFBO0VBQ0EsbUJBQUE7QUNDWjtBRENRO0VBQ0ksb0JBQUE7RUFBQSxhQUFBO0VBQ0EsOEJBQUE7RUFBQSw2QkFBQTtVQUFBLG1CQUFBO0VBQ0EseUJBQUE7VUFBQSxtQkFBQTtFQUNBLGtCQUFBO0FDQ1o7QURDWTtFQUNJLFlBQUE7RUFDQSxXQUFBO0VBQ0EsMkJBQUE7RUFDQSxzQkFBQTtFQUNBLDRCQUFBO0VBQ0EsbUJBQUE7QUNDaEI7QURFWTtFQUNFLGdCQUFBO0VBQ0EsZUFBQTtBQ0FkO0FERVk7RUFDSSxnQkFBQTtFQUNBLGVBQUE7QUNBaEI7QURHWTtFQUNJLGtCQUFBO0VBQ0EsVUFBQTtFQUNBLGlCQUFBO0FDRGhCO0FERWdCO0VBQ0csaUJBQUE7QUNBbkI7QURLUTtFQUNJLGtCQUFBO0FDSFo7QURLWTtFQUNJLGdCQUFBO0VBQ0EsZUFBQTtFQUNBLGdCQUFBO0FDSGhCO0FES1k7RUFDSSxlQUFBO0VBQ0EsZ0JBQUE7QUNIaEI7QURNZ0I7RUFDQSxtQ0FBQTtFQUNBLGdCQUFBO0VBQ0EsZUFBQTtFQUNBLGlCQUFBO0FDSmhCO0FETVk7RUFDSSxtQ0FBQTtFQUNBLG1CQUFBO0FDSmhCO0FES2dCO0VBQ0ksZUFBQTtFQUNBLGlCQUFBO0FDSHBCO0FES2dCO0VBQ0ksb0JBQUE7RUFBQSxhQUFBO0VBQ0EsOEJBQUE7RUFBQSw2QkFBQTtVQUFBLG1CQUFBO0VBQ0EseUJBQUE7VUFBQSw4QkFBQTtBQ0hwQjtBRElvQjtFQUNJLFdBQUE7RUFDQSxZQUFBO0VBQ0EsZUFBQTtBQ0Z4QjtBRE9ZO0VBQ0ksa0JBQUE7RUFDQSxXQUFBO0VBQ0EsMkJBQUE7QUNMaEI7QURRWTtFQUNJLGtCQUFBO0VBQ0EsWUFBQTtFQUNBLHlCQUFBO0VBQ0EsYUFBQTtFQUNBLG9DQUFBO0VBQ0EsWUFBQTtFQUNBLGdCQUFBO0VBQ0EsaUJBQUE7RUFDQSxnQ0FBQTtBQ05oQiIsImZpbGUiOiJzcmMvYXBwL3BhZ2VzL29yZGVycy9vcmRlcnMucGFnZS5zY3NzIiwic291cmNlc0NvbnRlbnQiOlsiIC5zZWdtZW50X2RpdntcbiAgICAgICAgZGlzcGxheTogZmxleDtcbiAgICAgICAgbWFyZ2luLXRvcDogMjBweDtcbiAgICAgICAgYm9yZGVyLWJvdHRvbTogMXB4IHNvbGlkIGxpZ2h0Z3JheTtcbiAgICAgICAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQ7XG4gICAgICAgIGlvbi1sYWJlbCB7XG4gICAgICAgICAgICBjb2xvcjogZ3JheTtcbiAgICAgICAgICAgIHBhZGRpbmctYm90dG9tOiAxMHB4O1xuICAgICAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgIH1cbiAgICAgICAgLmFjdGl2ZXtcbiAgICAgICAgICAgIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCByZWQ7XG4gICAgICAgIH1cbn1cbi5tYWluX2NvbnRlbnRfZGl2e1xuICAgIHdpZHRoOiAxMDAlO1xuICAgIC5jZW50ZW50X2RpdntcbiAgICAgICAgcGFkZGluZzogMjBweDtcblxuICAgICAgICBpb24tbGFiZWwge1xuICAgICAgICAgICAgZGlzcGxheTogYmxvY2s7XG4gICAgICAgIH1cbiAgICB9XG5cbiAgICAuY2FyZF9kaXZ7XG4gICAgICAgIHdpZHRoOiAxMDAlO1xuICAgICAgICBib3gtc2hhZG93OiAwcHggMXB4IDNweCByZ2JhKDAsMCwwLDAuMik7XG4gICAgICAgIGJvcmRlci1yYWRpdXM6IDEwcHg7XG4gICAgICAgIHBhZGRpbmc6IDE1cHg7XG4gICAgICAgIG1hcmdpbi1ib3R0b206IDIwcHg7XG4gICAgICAgIGJvcmRlcjogMC41cHggc29saWQgbGlnaHRncmF5O1xuXG4gICAgICAgIC5saW5lX2RpdntcbiAgICAgICAgICAgIGhlaWdodDogMXB4O1xuICAgICAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kOiBsaWdodGdyYXk7XG4gICAgICAgICAgICBtYXJnaW4tdG9wOiAxMHB4O1xuICAgICAgICAgICAgbWFyZ2luLWJvdHRvbTogMTBweDtcbiAgICAgICAgfVxuICAgICAgICAucmVzdG9fZGV0YWlse1xuICAgICAgICAgICAgZGlzcGxheTogZmxleDtcbiAgICAgICAgICAgIGZsZXgtZGlyZWN0aW9uOiByb3c7XG4gICAgICAgICAgICBhbGlnbi1pdGVtczogY2VudGVyO1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICBcbiAgICAgICAgICAgIC5iYWNrX2ltYWdle1xuICAgICAgICAgICAgICAgIGhlaWdodDogNTBweDtcbiAgICAgICAgICAgICAgICB3aWR0aDogNTBweDtcbiAgICAgICAgICAgICAgICBiYWNrZ3JvdW5kLXBvc2l0aW9uOiBjZW50ZXI7XG4gICAgICAgICAgICAgICAgYmFja2dyb3VuZC1zaXplOiBjb3ZlcjtcbiAgICAgICAgICAgICAgICBiYWNrZ3JvdW5kLXJlcGVhdDogbm8tcmVwZWF0O1xuICAgICAgICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDEwMCU7XG4gICAgICAgICAgICB9XG5cbiAgICAgICAgICAgIC5yZXNfbmFtZXtcbiAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IDYwMDsgIFxuICAgICAgICAgICAgICBmb250LXNpemU6IDE0cHg7XG4gICAgICAgICAgICB9IFxuICAgICAgICAgICAgLnJlc19sb2NhdGlvbntcbiAgICAgICAgICAgICAgICBjb2xvcjogbGlnaHRncmF5O1xuICAgICAgICAgICAgICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICAgICAgICAgIH1cblxuICAgICAgICAgICAgLm9yZGVyX2lke1xuICAgICAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgICAgICByaWdodDogNXB4O1xuICAgICAgICAgICAgICAgIGZvbnQtc2l6ZTogLjZyZW07XG4gICAgICAgICAgICAgICAgaW9uLWxhYmVsIHtcbiAgICAgICAgICAgICAgICAgICB0ZXh0LWFsaWduOiByaWdodDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cblxuICAgICAgICAub3JkZXJfZGV0YWlse1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuXG4gICAgICAgICAgICAuaGVhZF9ncmF5e1xuICAgICAgICAgICAgICAgIGNvbG9yOiBsaWdodGdyYXk7XG4gICAgICAgICAgICAgICAgZm9udC1zaXplOiAxM3B4O1xuICAgICAgICAgICAgICAgIG1hcmdpbi10b3A6IDEwcHg7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAuc21hbGxfbGJse1xuICAgICAgICAgICAgICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICAgICAgICAgICAgICBmb250LXdlaWdodDogNjAwO1xuICAgICAgICAgICAgfVxuXG4gICAgICAgICAgICAgICAgLmJvcmRlcl9ib3R0b217XG4gICAgICAgICAgICAgICAgYm9yZGVyLWJvdHRvbTogMXB4IGRhc2hlZCBsaWdodGdyYXk7XG4gICAgICAgICAgICAgICAgcGFkZGluZzogNXB4IDBweDtcbiAgICAgICAgICAgICAgICBmb250LXNpemU6IDE1cHg7XG4gICAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IGJvbGQ7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAuc3ViTmFtZXN7XG4gICAgICAgICAgICAgICAgYm9yZGVyLWJvdHRvbTogMXB4IGRhc2hlZCBsaWdodGdyYXk7XG4gICAgICAgICAgICAgICAgcGFkZGluZy1ib3R0b206IDVweDtcbiAgICAgICAgICAgICAgICAuZm9vZF90aXRsZXtcbiAgICAgICAgICAgICAgICAgICAgZm9udC1zaXplOiAxNXB4O1xuICAgICAgICAgICAgICAgICAgICBmb250LXdlaWdodDogYm9sZDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICAgICAgLmZsZXhfdGl0bGVze1xuICAgICAgICAgICAgICAgICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgICAgICAgICAgICAgICBmbGV4LWRpcmVjdGlvbjogcm93O1xuICAgICAgICAgICAgICAgICAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG4gICAgICAgICAgICAgICAgICAgIC5zdWJfbmFtZXtcbiAgICAgICAgICAgICAgICAgICAgICAgIG1hcmdpbjogMHB4O1xuICAgICAgICAgICAgICAgICAgICAgICAgY29sb3I6IGJsYWNrO1xuICAgICAgICAgICAgICAgICAgICAgICAgZm9udC1zaXplOiAxMnB4O1xuICAgICAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuXG4gICAgICAgICAgICAucHJpemV7XG4gICAgICAgICAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICAgICAgICAgIHJpZ2h0OiAzNXB4O1xuICAgICAgICAgICAgICAgIGZvbnQtd2VpZ2h0OiA2MDAgIWltcG9ydGFudDtcbiAgICAgICAgICAgIH1cblxuICAgICAgICAgICAgLnBheW1lbnRfc3RhdHVze1xuICAgICAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgICAgICByaWdodDogLTE1cHg7XG4gICAgICAgICAgICAgICAgdGV4dC10cmFuc2Zvcm06IHVwcGVyY2FzZTtcbiAgICAgICAgICAgICAgICBib3R0b206IC0xNXB4O1xuICAgICAgICAgICAgICAgIGJhY2tncm91bmQ6IHZhcigtLWlvbi1jb2xvci1wcmltYXJ5KTtcbiAgICAgICAgICAgICAgICBjb2xvcjogd2hpdGU7XG4gICAgICAgICAgICAgICAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgICAgICAgICAgICAgICBwYWRkaW5nOiA4cHggMTJweDtcbiAgICAgICAgICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMTBweDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbn0iLCIuc2VnbWVudF9kaXYge1xuICBkaXNwbGF5OiBmbGV4O1xuICBtYXJnaW4tdG9wOiAyMHB4O1xuICBib3JkZXItYm90dG9tOiAxcHggc29saWQgbGlnaHRncmF5O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWFyb3VuZDtcbn1cbi5zZWdtZW50X2RpdiBpb24tbGFiZWwge1xuICBjb2xvcjogZ3JheTtcbiAgcGFkZGluZy1ib3R0b206IDEwcHg7XG4gIHdpZHRoOiAxMDAlO1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG59XG4uc2VnbWVudF9kaXYgLmFjdGl2ZSB7XG4gIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCByZWQ7XG59XG5cbi5tYWluX2NvbnRlbnRfZGl2IHtcbiAgd2lkdGg6IDEwMCU7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2VudGVudF9kaXYge1xuICBwYWRkaW5nOiAyMHB4O1xufVxuLm1haW5fY29udGVudF9kaXYgLmNlbnRlbnRfZGl2IGlvbi1sYWJlbCB7XG4gIGRpc3BsYXk6IGJsb2NrO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IHtcbiAgd2lkdGg6IDEwMCU7XG4gIGJveC1zaGFkb3c6IDBweCAxcHggM3B4IHJnYmEoMCwgMCwgMCwgMC4yKTtcbiAgYm9yZGVyLXJhZGl1czogMTBweDtcbiAgcGFkZGluZzogMTVweDtcbiAgbWFyZ2luLWJvdHRvbTogMjBweDtcbiAgYm9yZGVyOiAwLjVweCBzb2xpZCBsaWdodGdyYXk7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLmxpbmVfZGl2IHtcbiAgaGVpZ2h0OiAxcHg7XG4gIHdpZHRoOiAxMDAlO1xuICBiYWNrZ3JvdW5kOiBsaWdodGdyYXk7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG4gIG1hcmdpbi1ib3R0b206IDEwcHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLnJlc3RvX2RldGFpbCB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGZsZXgtZGlyZWN0aW9uOiByb3c7XG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAucmVzdG9fZGV0YWlsIC5iYWNrX2ltYWdlIHtcbiAgaGVpZ2h0OiA1MHB4O1xuICB3aWR0aDogNTBweDtcbiAgYmFja2dyb3VuZC1wb3NpdGlvbjogY2VudGVyO1xuICBiYWNrZ3JvdW5kLXNpemU6IGNvdmVyO1xuICBiYWNrZ3JvdW5kLXJlcGVhdDogbm8tcmVwZWF0O1xuICBib3JkZXItcmFkaXVzOiAxMDAlO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IC5yZXN0b19kZXRhaWwgLnJlc19uYW1lIHtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgZm9udC1zaXplOiAxNHB4O1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IC5yZXN0b19kZXRhaWwgLnJlc19sb2NhdGlvbiB7XG4gIGNvbG9yOiBsaWdodGdyYXk7XG4gIGZvbnQtc2l6ZTogMTRweDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAucmVzdG9fZGV0YWlsIC5vcmRlcl9pZCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IDVweDtcbiAgZm9udC1zaXplOiAwLjZyZW07XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLnJlc3RvX2RldGFpbCAub3JkZXJfaWQgaW9uLWxhYmVsIHtcbiAgdGV4dC1hbGlnbjogcmlnaHQ7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLm9yZGVyX2RldGFpbCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAub3JkZXJfZGV0YWlsIC5oZWFkX2dyYXkge1xuICBjb2xvcjogbGlnaHRncmF5O1xuICBmb250LXNpemU6IDEzcHg7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLm9yZGVyX2RldGFpbCAuc21hbGxfbGJsIHtcbiAgZm9udC1zaXplOiAxNHB4O1xuICBmb250LXdlaWdodDogNjAwO1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IC5vcmRlcl9kZXRhaWwgLmJvcmRlcl9ib3R0b20ge1xuICBib3JkZXItYm90dG9tOiAxcHggZGFzaGVkIGxpZ2h0Z3JheTtcbiAgcGFkZGluZzogNXB4IDBweDtcbiAgZm9udC1zaXplOiAxNXB4O1xuICBmb250LXdlaWdodDogYm9sZDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAub3JkZXJfZGV0YWlsIC5zdWJOYW1lcyB7XG4gIGJvcmRlci1ib3R0b206IDFweCBkYXNoZWQgbGlnaHRncmF5O1xuICBwYWRkaW5nLWJvdHRvbTogNXB4O1xufVxuLm1haW5fY29udGVudF9kaXYgLmNhcmRfZGl2IC5vcmRlcl9kZXRhaWwgLnN1Yk5hbWVzIC5mb29kX3RpdGxlIHtcbiAgZm9udC1zaXplOiAxNXB4O1xuICBmb250LXdlaWdodDogYm9sZDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAub3JkZXJfZGV0YWlsIC5zdWJOYW1lcyAuZmxleF90aXRsZXMge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogcm93O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG59XG4ubWFpbl9jb250ZW50X2RpdiAuY2FyZF9kaXYgLm9yZGVyX2RldGFpbCAuc3ViTmFtZXMgLmZsZXhfdGl0bGVzIC5zdWJfbmFtZSB7XG4gIG1hcmdpbjogMHB4O1xuICBjb2xvcjogYmxhY2s7XG4gIGZvbnQtc2l6ZTogMTJweDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAub3JkZXJfZGV0YWlsIC5wcml6ZSB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IDM1cHg7XG4gIGZvbnQtd2VpZ2h0OiA2MDAgIWltcG9ydGFudDtcbn1cbi5tYWluX2NvbnRlbnRfZGl2IC5jYXJkX2RpdiAub3JkZXJfZGV0YWlsIC5wYXltZW50X3N0YXR1cyB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IC0xNXB4O1xuICB0ZXh0LXRyYW5zZm9ybTogdXBwZXJjYXNlO1xuICBib3R0b206IC0xNXB4O1xuICBiYWNrZ3JvdW5kOiB2YXIoLS1pb24tY29sb3ItcHJpbWFyeSk7XG4gIGNvbG9yOiB3aGl0ZTtcbiAgZm9udC13ZWlnaHQ6IDYwMDtcbiAgcGFkZGluZzogOHB4IDEycHg7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAxMHB4O1xufSJdfQ== */");

/***/ }),

/***/ "./src/app/pages/orders/orders.page.ts":
/*!*********************************************!*\
  !*** ./src/app/pages/orders/orders.page.ts ***!
  \*********************************************/
/*! exports provided: OrdersPage */
/***/ (function(module, __webpack_exports__, __webpack_require__) {

"use strict";
__webpack_require__.r(__webpack_exports__);
/* harmony export (binding) */ __webpack_require__.d(__webpack_exports__, "OrdersPage", function() { return OrdersPage; });
/* harmony import */ var tslib__WEBPACK_IMPORTED_MODULE_0__ = __webpack_require__(/*! tslib */ "./node_modules/tslib/tslib.es6.js");
/* harmony import */ var _angular_core__WEBPACK_IMPORTED_MODULE_1__ = __webpack_require__(/*! @angular/core */ "./node_modules/@angular/core/fesm2015/core.js");
/* harmony import */ var _angular_router__WEBPACK_IMPORTED_MODULE_2__ = __webpack_require__(/*! @angular/router */ "./node_modules/@angular/router/fesm2015/router.js");
/* harmony import */ var src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__ = __webpack_require__(/*! src/app/services/api.service */ "./src/app/services/api.service.ts");
/* harmony import */ var _angular_fire_firestore__WEBPACK_IMPORTED_MODULE_4__ = __webpack_require__(/*! @angular/fire/firestore */ "./node_modules/@angular/fire/firestore/es2015/index.js");
/* harmony import */ var src_app_services_util_service__WEBPACK_IMPORTED_MODULE_5__ = __webpack_require__(/*! src/app/services/util.service */ "./src/app/services/util.service.ts");






let OrdersPage = class OrdersPage {
    constructor(router, api, util, adb) {
        this.router = router;
        this.api = api;
        this.util = util;
        this.adb = adb;
        this.seg_id = 1;
        this.orders = [];
        this.dummy = Array(50);
        // this.getOrders();
        if (localStorage.getItem('uid')) {
            this.adb.collection('orders', ref => ref.where('driverId', '==', localStorage.getItem('uid'))).snapshotChanges().subscribe((data) => {
                console.log('paylaoddddd----->>>>', data);
                if (data) {
                    this.getOrders();
                }
            }, error => {
                console.log(error);
            });
        }
    }
    ngOnInit() {
    }
    onClick(val) {
        this.seg_id = val;
    }
    getOrders() {
        this.orders = [];
        this.oldOrders = [];
        this.api.getMyOrders(localStorage.getItem('uid')).then((data) => {
            this.dummy = [];
            console.log(data);
            if (data) {
                this.orders = [];
                this.oldOrders = [];
                data.forEach(element => {
                    element.order = JSON.parse(element.order);
                    if (element.status === 'delivered' || element.status === 'cancel' || element.status === 'rejected') {
                        this.oldOrders.push(element);
                    }
                    else {
                        this.orders.push(element);
                    }
                });
            }
        }).catch(error => {
            this.dummy = [];
            console.log('eror', error);
        });
    }
    goToOrderDetail(ids) {
        const navData = {
            queryParams: {
                id: ids
            }
        };
        this.router.navigate(['/order-detail'], navData);
    }
    getProfilePic(item) {
        return item && item.cover ? item.cover : 'assets/imgs/user.jpg';
    }
    getCurrency() {
        return this.util.getCurrecySymbol();
    }
};
OrdersPage.ctorParameters = () => [
    { type: _angular_router__WEBPACK_IMPORTED_MODULE_2__["Router"] },
    { type: src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__["ApiService"] },
    { type: src_app_services_util_service__WEBPACK_IMPORTED_MODULE_5__["UtilService"] },
    { type: _angular_fire_firestore__WEBPACK_IMPORTED_MODULE_4__["AngularFirestore"] }
];
OrdersPage = tslib__WEBPACK_IMPORTED_MODULE_0__["__decorate"]([
    Object(_angular_core__WEBPACK_IMPORTED_MODULE_1__["Component"])({
        selector: 'app-orders',
        template: tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"](__webpack_require__(/*! raw-loader!./orders.page.html */ "./node_modules/raw-loader/dist/cjs.js!./src/app/pages/orders/orders.page.html")).default,
        styles: [tslib__WEBPACK_IMPORTED_MODULE_0__["__importDefault"](__webpack_require__(/*! ./orders.page.scss */ "./src/app/pages/orders/orders.page.scss")).default]
    }),
    tslib__WEBPACK_IMPORTED_MODULE_0__["__metadata"]("design:paramtypes", [_angular_router__WEBPACK_IMPORTED_MODULE_2__["Router"],
        src_app_services_api_service__WEBPACK_IMPORTED_MODULE_3__["ApiService"],
        src_app_services_util_service__WEBPACK_IMPORTED_MODULE_5__["UtilService"],
        _angular_fire_firestore__WEBPACK_IMPORTED_MODULE_4__["AngularFirestore"]])
], OrdersPage);



/***/ })

}]);
//# sourceMappingURL=default~orders-orders-module~pages-orders-orders-module-es2015.js.map