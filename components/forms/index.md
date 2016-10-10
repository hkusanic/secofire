---
title: SecoFire Style Guidelines
---
<html>
  {% include head.html %}
  <body>
	{% include header.html %}
	<div id="main_content_wrap" class="outer">
		<section id="main_content" class="inner">
			<h3>
				<a id="welcome-to-github-pages" class="anchor" href="#welcome-to-github-pages" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				SecoFire Forms.
			</h3>
			
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus molestie libero vel orci volutpat, ut maximus velit placerat. In at condimentum lectus. Maecenas fringilla varius ligula vel imperdiet. Etiam eget lobortis lectus. Morbi imperdiet turpis massa, in dapibus arcu sodales eu. Donec vitae ligula id libero placerat gravida et lobortis eros. Suspendisse dictum blandit libero quis sodales.<a href="https://guides.github.com/features/mastering-markdown/">Link example 1</a>, Aliquam lobortis tellus sit amet ante euismod, et semper nisi ultricies. Nullam convallis diam ante, non euismod justo aliquam eget. Vestibulum sit amet sagittis tellus. Vestibulum at aliquet risus.</p>
			<img src=""https://hkusanic.github.io/secofire/images/form_section2.png" alt="Section element" height="269" width="1014">
			<!--BEGINING of Section element-->
	// 		<div>
	// 			<md-content layout="column" ng-if="$ctrl.area &amp;&amp; $ctrl.area._isHidden <= 0" layout-padding="" ng-class="{'seco-invalid-area' : !$ctrl.area._isValid}" class="layout-padding ng-scope _md layout-column seco-invalid-area" style="">
	// 			<h3 class="area-title ng-binding">1 - Neueröffnung oder wesentliche Änderung?</h3>
	// 			<div flex="" layout="column" ng-transclude="" class="layout-column flex">
	// 										<!-- ngIf: $ctrl.form && $ctrl.areas.size() > 0 && $ctrl.resources --><seco-fire-form-coor ng-if="$ctrl.form &amp;&amp; $ctrl.areas.size() > 0 &amp;&amp; $ctrl.resources" resources="$ctrl.resources" areas="$ctrl.areas" area="$ctrl.areas.get('1')" form="$ctrl.form" class="ng-scope ng-isolate-scope"><div layout-margin="" class="layout-margin">
	// 			<div>
	// 				<!-- ngIf: $ctrl._showCompanyOpening --><md-checkbox ng-if="$ctrl._showCompanyOpening" ng-disabled="$ctrl.form._viewMode" ng-model="$ctrl.form.CompanyOpening" aria-label="Neueröffnung einer Unternehmung (Gründung)" class="md-primary ng-pristine ng-untouched ng-valid ng-scope ng-empty" tabindex="0" type="checkbox" role="checkbox" aria-disabled="false" aria-checked="false" aria-invalid="false" style=""><div class="md-container md-ink-ripple" md-ink-ripple="" md-ink-ripple-checkbox=""><div class="md-icon"></div></div><div ng-transclude="" class="md-label"><span class="ng-binding ng-scope">
	// 					Neueröffnung einer Unternehmung (Gründung)
	// 				</span></div></md-checkbox><!-- end ngIf: $ctrl._showCompanyOpening -->
	// 				<seco-field-description description="$ctrl.resources.ReqFldDescCompanyOpening" class="ng-isolate-scope"><span class="seco-field-description ng-binding">
				
	// 		</span>
	// 		</seco-field-description>
	// 				<!-- ngIf: $ctrl._showCompanyAlreadyOpened || $ctrl._showCompanyNotYetOpened || $ctrl._showUploadCertificateOfRegistration -->
	// 			</div>
	// 			<div>
	// 				<!-- ngIf: $ctrl._showEssentialOperationRealignment --><md-checkbox ng-if="$ctrl._showEssentialOperationRealignment" ng-disabled="$ctrl.form._viewMode" ng-model="$ctrl.form.EssentialOperationRealignment" aria-label="Wesentliche Änderung der betrieblichen Tätigkeit einer bestehenden Unternehmung oder einer Betriebsstätte (Neuausrichtung)" class="md-primary ng-pristine ng-untouched ng-valid ng-scope ng-empty" tabindex="0" type="checkbox" role="checkbox" aria-disabled="false" aria-checked="false" aria-invalid="false" style=""><div class="md-container md-ink-ripple" md-ink-ripple="" md-ink-ripple-checkbox=""><div class="md-icon"></div></div><div ng-transclude="" class="md-label"><span class="ng-binding ng-scope">
	// 					Wesentliche Änderung der betrieblichen Tätigkeit einer bestehenden Unternehmung oder einer Betriebsstätte (Neuausrichtung)
	// 				</span></div></md-checkbox><!-- end ngIf: $ctrl._showEssentialOperationRealignment -->
	// 				<seco-field-description description="$ctrl.resources.ReqFldDescEssentialOperationRealignment" class="ng-isolate-scope"><span class="seco-field-description ng-binding">
				
	// 		</span>
	// 		</seco-field-description>
	// 			</div>
	// 		</div>
	// 		</seco-fire-form-coor><!-- end ngIf: $ctrl.form && $ctrl.areas.size() > 0 && $ctrl.resources -->
	// 								</div>
	// 				<!-- ngRepeat: error in $ctrl.area.errors -->
	// 			<seco-law-references area="$ctrl.area" class="ng-isolate-scope"><div class="seco-area-laws layout-column" layout="column">
	// 			<!-- ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws --><div class="seco-area-law ng-scope" ng-repeat="law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws">
	// 				<a href="https://www.admin.ch/opc/de/classified-compilation/20160348/index.html#a3" target="_blank" class="ng-binding">Art. 3 WBF-Anwendungsverordnung</a>
	// 			</div><!-- end ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws --><div class="seco-area-law ng-scope" ng-repeat="law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws">
	// 				<a href="https://www.admin.ch/opc/de/classified-compilation/20160348/index.html#a4" target="_blank" class="ng-binding">Art. 4 WBF-Anwendungsverordnung</a>
	// 			</div><!-- end ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws --><div class="seco-area-law ng-scope" ng-repeat="law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws">
	// 				<a href="https://www.admin.ch/opc/de/classified-compilation/20160348/index.html" target="_blank" class="ng-binding">WBF-Anwendungsverordnung; SR 901.022.2</a>
	// 			</div><!-- end ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws --><div class="seco-area-law ng-scope" ng-repeat="law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws">
	// 				<a href="https://www.admin.ch/opc/de/classified-compilation/19900333/index.html#a23" target="_blank" class="ng-binding">Art. 23 Abs. 3 StHG</a>
	// 			</div><!-- end ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws --><div class="seco-area-law ng-scope" ng-repeat="law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws">
	// 				<a href="https://www.admin.ch/opc/de/classified-compilation/19900333/index.html" target="_blank" class="ng-binding">StHG; SR 642.14</a>
	// 			</div><!-- end ngRepeat: law in ::$ctrl.lawReferences | filter: $ctrl.invalidLaws -->
	// 		</div>
	// 		</seco-law-references>
	// 		</md-content>
	// 		</div>
	// 		<p>Having trouble with Pages? Check out our <a href="https://help.github.com/pages">documentation</a> or <a href="https://github.com/contact">contact support</a> and we’ll help you sort it out.</p>
	// 	</section>
	// </div>
	<!--END of Section element-->
	
	{% include footer.html %}
	{% include scripts.html %}
	</body>
</html>
