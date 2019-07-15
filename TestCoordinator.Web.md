<a name='assembly'></a>
# TestCoordinator.Web

## Contents

- [ActionNames](#T-TestCoordinator-Web-Resources-ActionNames 'TestCoordinator.Web.Resources.ActionNames')
  - [CancelEditing](#F-TestCoordinator-Web-Resources-ActionNames-CancelEditing 'TestCoordinator.Web.Resources.ActionNames.CancelEditing')
  - [Create](#F-TestCoordinator-Web-Resources-ActionNames-Create 'TestCoordinator.Web.Resources.ActionNames.Create')
  - [Delete](#F-TestCoordinator-Web-Resources-ActionNames-Delete 'TestCoordinator.Web.Resources.ActionNames.Delete')
  - [Download](#F-TestCoordinator-Web-Resources-ActionNames-Download 'TestCoordinator.Web.Resources.ActionNames.Download')
  - [Edit](#F-TestCoordinator-Web-Resources-ActionNames-Edit 'TestCoordinator.Web.Resources.ActionNames.Edit')
  - [General](#F-TestCoordinator-Web-Resources-ActionNames-General 'TestCoordinator.Web.Resources.ActionNames.General')
  - [Index](#F-TestCoordinator-Web-Resources-ActionNames-Index 'TestCoordinator.Web.Resources.ActionNames.Index')
  - [Items](#F-TestCoordinator-Web-Resources-ActionNames-Items 'TestCoordinator.Web.Resources.ActionNames.Items')
  - [Start](#F-TestCoordinator-Web-Resources-ActionNames-Start 'TestCoordinator.Web.Resources.ActionNames.Start')
- [AreaViewModel](#T-TestCoordinator-Web-ViewModels-AreaViewModel 'TestCoordinator.Web.ViewModels.AreaViewModel')
  - [Assignee](#P-TestCoordinator-Web-ViewModels-AreaViewModel-Assignee 'TestCoordinator.Web.ViewModels.AreaViewModel.Assignee')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-AreaViewModel-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.AreaViewModel.ChildTypeDisplayName')
  - [Priority](#P-TestCoordinator-Web-ViewModels-AreaViewModel-Priority 'TestCoordinator.Web.ViewModels.AreaViewModel.Priority')
  - [CreateMappings(configuration)](#M-TestCoordinator-Web-ViewModels-AreaViewModel-CreateMappings-AutoMapper-IConfiguration- 'TestCoordinator.Web.ViewModels.AreaViewModel.CreateMappings(AutoMapper.IConfiguration)')
- [AreasController](#T-TestCoordinator-Web-Controllers-AreasController 'TestCoordinator.Web.Controllers.AreasController')
  - [#ctor()](#M-TestCoordinator-Web-Controllers-AreasController-#ctor 'TestCoordinator.Web.Controllers.AreasController.#ctor')
  - [BuildBreadcrumb(parentId)](#M-TestCoordinator-Web-Controllers-AreasController-BuildBreadcrumb-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.AreasController.BuildBreadcrumb(System.Nullable{System.Int32})')
  - [Create(viewModel,parentId)](#M-TestCoordinator-Web-Controllers-AreasController-Create-TestCoordinator-Web-ViewModels-AreaViewModel,System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.AreasController.Create(TestCoordinator.Web.ViewModels.AreaViewModel,System.Nullable{System.Int32})')
- [AttachmentViewModel](#T-TestCoordinator-Web-ViewModels-AttachmentViewModel 'TestCoordinator.Web.ViewModels.AttachmentViewModel')
  - [FileName](#P-TestCoordinator-Web-ViewModels-AttachmentViewModel-FileName 'TestCoordinator.Web.ViewModels.AttachmentViewModel.FileName')
  - [Id](#P-TestCoordinator-Web-ViewModels-AttachmentViewModel-Id 'TestCoordinator.Web.ViewModels.AttachmentViewModel.Id')
- [AttachmentsController](#T-TestCoordinator-Web-Controllers-AttachmentsController 'TestCoordinator.Web.Controllers.AttachmentsController')
  - [UnitOfWork](#P-TestCoordinator-Web-Controllers-AttachmentsController-UnitOfWork 'TestCoordinator.Web.Controllers.AttachmentsController.UnitOfWork')
  - [Delete(id)](#M-TestCoordinator-Web-Controllers-AttachmentsController-Delete-System-Guid- 'TestCoordinator.Web.Controllers.AttachmentsController.Delete(System.Guid)')
  - [DeleteAll()](#M-TestCoordinator-Web-Controllers-AttachmentsController-DeleteAll 'TestCoordinator.Web.Controllers.AttachmentsController.DeleteAll')
  - [Download(id)](#M-TestCoordinator-Web-Controllers-AttachmentsController-Download-System-Guid- 'TestCoordinator.Web.Controllers.AttachmentsController.Download(System.Guid)')
  - [FileUpload()](#M-TestCoordinator-Web-Controllers-AttachmentsController-FileUpload 'TestCoordinator.Web.Controllers.AttachmentsController.FileUpload')
- [AttributeNames](#T-TestCoordinator-Web-Resources-AttributeNames 'TestCoordinator.Web.Resources.AttributeNames')
  - [Name](#F-TestCoordinator-Web-Resources-AttributeNames-Name 'TestCoordinator.Web.Resources.AttributeNames.Name')
- [AutoMapperConfig](#T-TestCoordinator-Web-Configurations-AutoMapperConfig 'TestCoordinator.Web.Configurations.AutoMapperConfig')
  - [RegisterMappings()](#M-TestCoordinator-Web-Configurations-AutoMapperConfig-RegisterMappings 'TestCoordinator.Web.Configurations.AutoMapperConfig.RegisterMappings')
- [AutomatedTestViewModel](#T-TestCoordinator-Web-ViewModels-AutomatedTestViewModel 'TestCoordinator.Web.ViewModels.AutomatedTestViewModel')
  - [Fixture](#P-TestCoordinator-Web-ViewModels-AutomatedTestViewModel-Fixture 'TestCoordinator.Web.ViewModels.AutomatedTestViewModel.Fixture')
  - [TestName](#P-TestCoordinator-Web-ViewModels-AutomatedTestViewModel-TestName 'TestCoordinator.Web.ViewModels.AutomatedTestViewModel.TestName')
- [AutomatedTestsController](#T-TestCoordinator-Web-Controllers-AutomatedTestsController 'TestCoordinator.Web.Controllers.AutomatedTestsController')
  - [GetManageScreen(automatedTests)](#M-TestCoordinator-Web-Controllers-AutomatedTestsController-GetManageScreen-System-String- 'TestCoordinator.Web.Controllers.AutomatedTestsController.GetManageScreen(System.String)')
  - [NewTest()](#M-TestCoordinator-Web-Controllers-AutomatedTestsController-NewTest 'TestCoordinator.Web.Controllers.AutomatedTestsController.NewTest')
- [Breadcrumb](#T-TestCoordinator-Web-Models-Breadcrumb 'TestCoordinator.Web.Models.Breadcrumb')
  - [#ctor(nodes)](#M-TestCoordinator-Web-Models-Breadcrumb-#ctor-TestCoordinator-Web-Models-Node[]- 'TestCoordinator.Web.Models.Breadcrumb.#ctor(TestCoordinator.Web.Models.Node[])')
  - [#ctor()](#M-TestCoordinator-Web-Models-Breadcrumb-#ctor 'TestCoordinator.Web.Models.Breadcrumb.#ctor')
  - [Nodes](#P-TestCoordinator-Web-Models-Breadcrumb-Nodes 'TestCoordinator.Web.Models.Breadcrumb.Nodes')
  - [AddNode(node)](#M-TestCoordinator-Web-Models-Breadcrumb-AddNode-TestCoordinator-Web-Models-Node- 'TestCoordinator.Web.Models.Breadcrumb.AddNode(TestCoordinator.Web.Models.Node)')
  - [Equals(obj)](#M-TestCoordinator-Web-Models-Breadcrumb-Equals-System-Object- 'TestCoordinator.Web.Models.Breadcrumb.Equals(System.Object)')
  - [GetHashCode()](#M-TestCoordinator-Web-Models-Breadcrumb-GetHashCode 'TestCoordinator.Web.Models.Breadcrumb.GetHashCode')
- [BugViewModel](#T-TestCoordinator-Web-ViewModels-BugViewModel 'TestCoordinator.Web.ViewModels.BugViewModel')
  - [BugTrackingSystemItemUrl](#P-TestCoordinator-Web-ViewModels-BugViewModel-BugTrackingSystemItemUrl 'TestCoordinator.Web.ViewModels.BugViewModel.BugTrackingSystemItemUrl')
  - [Title](#P-TestCoordinator-Web-ViewModels-BugViewModel-Title 'TestCoordinator.Web.ViewModels.BugViewModel.Title')
- [BugsController](#T-TestCoordinator-Web-Controllers-BugsController 'TestCoordinator.Web.Controllers.BugsController')
  - [GetManageScreen(bugs)](#M-TestCoordinator-Web-Controllers-BugsController-GetManageScreen-System-String- 'TestCoordinator.Web.Controllers.BugsController.GetManageScreen(System.String)')
  - [NewBug()](#M-TestCoordinator-Web-Controllers-BugsController-NewBug 'TestCoordinator.Web.Controllers.BugsController.NewBug')
- [BundleConfig](#T-TestCoordinator-Web-Configurations-BundleConfig 'TestCoordinator.Web.Configurations.BundleConfig')
  - [BootstrapScriptsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-BootstrapScriptsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.BootstrapScriptsBundlePath')
  - [BootstrapStylesBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-BootstrapStylesBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.BootstrapStylesBundlePath')
  - [ChartJsScriptsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-ChartJsScriptsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.ChartJsScriptsBundlePath')
  - [DataTablesScriptsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-DataTablesScriptsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.DataTablesScriptsBundlePath')
  - [DataTablesStylesBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-DataTablesStylesBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.DataTablesStylesBundlePath')
  - [HideSideSectionsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-HideSideSectionsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.HideSideSectionsBundlePath')
  - [JQueryBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-JQueryBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.JQueryBundlePath')
  - [JQueryFileUploadScriptsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-JQueryFileUploadScriptsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.JQueryFileUploadScriptsBundlePath')
  - [JQueryFileUploadStylesBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-JQueryFileUploadStylesBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.JQueryFileUploadStylesBundlePath')
  - [JQueryValidationBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-JQueryValidationBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.JQueryValidationBundlePath')
  - [SiteScriptsPath](#F-TestCoordinator-Web-Configurations-BundleConfig-SiteScriptsPath 'TestCoordinator.Web.Configurations.BundleConfig.SiteScriptsPath')
  - [SiteStylesPath](#F-TestCoordinator-Web-Configurations-BundleConfig-SiteStylesPath 'TestCoordinator.Web.Configurations.BundleConfig.SiteStylesPath')
  - [TestCasesScriptsBundlePath](#F-TestCoordinator-Web-Configurations-BundleConfig-TestCasesScriptsBundlePath 'TestCoordinator.Web.Configurations.BundleConfig.TestCasesScriptsBundlePath')
  - [TinyMceEditorScriptsPath](#F-TestCoordinator-Web-Configurations-BundleConfig-TinyMceEditorScriptsPath 'TestCoordinator.Web.Configurations.BundleConfig.TinyMceEditorScriptsPath')
  - [RegisterBundles(bundles)](#M-TestCoordinator-Web-Configurations-BundleConfig-RegisterBundles-System-Web-Optimization-BundleCollection- 'TestCoordinator.Web.Configurations.BundleConfig.RegisterBundles(System.Web.Optimization.BundleCollection)')
- [ChartItemViewModel](#T-TestCoordinator-Web-ViewModels-ChartItemViewModel 'TestCoordinator.Web.ViewModels.ChartItemViewModel')
  - [HexColor](#P-TestCoordinator-Web-ViewModels-ChartItemViewModel-HexColor 'TestCoordinator.Web.ViewModels.ChartItemViewModel.HexColor')
  - [Label](#P-TestCoordinator-Web-ViewModels-ChartItemViewModel-Label 'TestCoordinator.Web.ViewModels.ChartItemViewModel.Label')
  - [Value](#P-TestCoordinator-Web-ViewModels-ChartItemViewModel-Value 'TestCoordinator.Web.ViewModels.ChartItemViewModel.Value')
- [ControllerBase\`2](#T-TestCoordinator-Web-Controllers-ControllerBase`2 'TestCoordinator.Web.Controllers.ControllerBase`2')
  - [#ctor(viewModel)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-#ctor-`1- 'TestCoordinator.Web.Controllers.ControllerBase`2.#ctor(`1)')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Web-Controllers-ControllerBase`2-ChildItemsRouteFormat 'TestCoordinator.Web.Controllers.ControllerBase`2.ChildItemsRouteFormat')
  - [CurrentTypeDisplayNameInPlural](#P-TestCoordinator-Web-Controllers-ControllerBase`2-CurrentTypeDisplayNameInPlural 'TestCoordinator.Web.Controllers.ControllerBase`2.CurrentTypeDisplayNameInPlural')
  - [CurrentTypeDisplayNameInSingular](#P-TestCoordinator-Web-Controllers-ControllerBase`2-CurrentTypeDisplayNameInSingular 'TestCoordinator.Web.Controllers.ControllerBase`2.CurrentTypeDisplayNameInSingular')
  - [StringResources](#P-TestCoordinator-Web-Controllers-ControllerBase`2-StringResources 'TestCoordinator.Web.Controllers.ControllerBase`2.StringResources')
  - [UnitOfWork](#P-TestCoordinator-Web-Controllers-ControllerBase`2-UnitOfWork 'TestCoordinator.Web.Controllers.ControllerBase`2.UnitOfWork')
  - [ViewModel](#P-TestCoordinator-Web-Controllers-ControllerBase`2-ViewModel 'TestCoordinator.Web.Controllers.ControllerBase`2.ViewModel')
  - [BuildBreadcrumb(parentId)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-BuildBreadcrumb-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.ControllerBase`2.BuildBreadcrumb(System.Nullable{System.Int32})')
  - [CancelEditing(viewModel)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-CancelEditing-`1- 'TestCoordinator.Web.Controllers.ControllerBase`2.CancelEditing(`1)')
  - [Create(viewModel,parentId)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Create-`1,System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.ControllerBase`2.Create(`1,System.Nullable{System.Int32})')
  - [Create(parentId)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Create-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.ControllerBase`2.Create(System.Nullable{System.Int32})')
  - [Delete(id)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Delete-System-Int32- 'TestCoordinator.Web.Controllers.ControllerBase`2.Delete(System.Int32)')
  - [Edit(viewModel)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Edit-`1- 'TestCoordinator.Web.Controllers.ControllerBase`2.Edit(`1)')
  - [Edit(id)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Edit-System-Int32- 'TestCoordinator.Web.Controllers.ControllerBase`2.Edit(System.Int32)')
  - [Items(parentId,sort)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Items-System-Nullable{System-Int32},System-String- 'TestCoordinator.Web.Controllers.ControllerBase`2.Items(System.Nullable{System.Int32},System.String)')
  - [Items(viewModels)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-Items-System-Collections-Generic-IEnumerable{`1}- 'TestCoordinator.Web.Controllers.ControllerBase`2.Items(System.Collections.Generic.IEnumerable{`1})')
  - [OnActionExecuted(filterContext)](#M-TestCoordinator-Web-Controllers-ControllerBase`2-OnActionExecuted-System-Web-Mvc-ActionExecutedContext- 'TestCoordinator.Web.Controllers.ControllerBase`2.OnActionExecuted(System.Web.Mvc.ActionExecutedContext)')
- [ControllerNames](#T-TestCoordinator-Web-Resources-ControllerNames 'TestCoordinator.Web.Resources.ControllerNames')
  - [Attachments](#F-TestCoordinator-Web-Resources-ControllerNames-Attachments 'TestCoordinator.Web.Resources.ControllerNames.Attachments')
  - [Error](#F-TestCoordinator-Web-Resources-ControllerNames-Error 'TestCoordinator.Web.Resources.ControllerNames.Error')
  - [Products](#F-TestCoordinator-Web-Resources-ControllerNames-Products 'TestCoordinator.Web.Resources.ControllerNames.Products')
  - [RegressionTesting](#F-TestCoordinator-Web-Resources-ControllerNames-RegressionTesting 'TestCoordinator.Web.Resources.ControllerNames.RegressionTesting')
  - [Statistics](#F-TestCoordinator-Web-Resources-ControllerNames-Statistics 'TestCoordinator.Web.Resources.ControllerNames.Statistics')
- [CustomSelectListItem](#T-TestCoordinator-Web-Custom-CustomSelectListItem 'TestCoordinator.Web.Custom.CustomSelectListItem')
  - [Equals(obj)](#M-TestCoordinator-Web-Custom-CustomSelectListItem-Equals-System-Object- 'TestCoordinator.Web.Custom.CustomSelectListItem.Equals(System.Object)')
  - [GetHashCode()](#M-TestCoordinator-Web-Custom-CustomSelectListItem-GetHashCode 'TestCoordinator.Web.Custom.CustomSelectListItem.GetHashCode')
- [DemoDataController](#T-TestCoordinator-Web-Controllers-DemoDataController 'TestCoordinator.Web.Controllers.DemoDataController')
  - [UnitOfWork](#P-TestCoordinator-Web-Controllers-DemoDataController-UnitOfWork 'TestCoordinator.Web.Controllers.DemoDataController.UnitOfWork')
  - [Cleanup()](#M-TestCoordinator-Web-Controllers-DemoDataController-Cleanup 'TestCoordinator.Web.Controllers.DemoDataController.Cleanup')
  - [Generate()](#M-TestCoordinator-Web-Controllers-DemoDataController-Generate 'TestCoordinator.Web.Controllers.DemoDataController.Generate')
- [ErrorController](#T-TestCoordinator-Web-Controllers-ErrorController 'TestCoordinator.Web.Controllers.ErrorController')
  - [Index()](#M-TestCoordinator-Web-Controllers-ErrorController-Index 'TestCoordinator.Web.Controllers.ErrorController.Index')
  - [NotFound()](#M-TestCoordinator-Web-Controllers-ErrorController-NotFound 'TestCoordinator.Web.Controllers.ErrorController.NotFound')
- [ErrorViewModel](#T-TestCoordinator-Web-ViewModels-ErrorViewModel 'TestCoordinator.Web.ViewModels.ErrorViewModel')
  - [Details](#P-TestCoordinator-Web-ViewModels-ErrorViewModel-Details 'TestCoordinator.Web.ViewModels.ErrorViewModel.Details')
  - [Heading](#P-TestCoordinator-Web-ViewModels-ErrorViewModel-Heading 'TestCoordinator.Web.ViewModels.ErrorViewModel.Heading')
  - [Title](#P-TestCoordinator-Web-ViewModels-ErrorViewModel-Title 'TestCoordinator.Web.ViewModels.ErrorViewModel.Title')
- [FeatureViewModel](#T-TestCoordinator-Web-ViewModels-FeatureViewModel 'TestCoordinator.Web.ViewModels.FeatureViewModel')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-FeatureViewModel-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.FeatureViewModel.ChildTypeDisplayName')
  - [CreateMappings(configuration)](#M-TestCoordinator-Web-ViewModels-FeatureViewModel-CreateMappings-AutoMapper-IConfiguration- 'TestCoordinator.Web.ViewModels.FeatureViewModel.CreateMappings(AutoMapper.IConfiguration)')
- [FeaturesController](#T-TestCoordinator-Web-Controllers-FeaturesController 'TestCoordinator.Web.Controllers.FeaturesController')
  - [#ctor()](#M-TestCoordinator-Web-Controllers-FeaturesController-#ctor 'TestCoordinator.Web.Controllers.FeaturesController.#ctor')
  - [BuildBreadcrumb(parentId)](#M-TestCoordinator-Web-Controllers-FeaturesController-BuildBreadcrumb-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.FeaturesController.BuildBreadcrumb(System.Nullable{System.Int32})')
  - [Create(viewModel,parentId)](#M-TestCoordinator-Web-Controllers-FeaturesController-Create-TestCoordinator-Web-ViewModels-FeatureViewModel,System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.FeaturesController.Create(TestCoordinator.Web.ViewModels.FeatureViewModel,System.Nullable{System.Int32})')
- [FilterConfig](#T-TestCoordinator-Web-Configurations-FilterConfig 'TestCoordinator.Web.Configurations.FilterConfig')
  - [RegisterGlobalFilters(filters)](#M-TestCoordinator-Web-Configurations-FilterConfig-RegisterGlobalFilters-System-Web-Mvc-GlobalFilterCollection- 'TestCoordinator.Web.Configurations.FilterConfig.RegisterGlobalFilters(System.Web.Mvc.GlobalFilterCollection)')
- [HtmlHelperExtensions](#T-TestCoordinator-Web-Custom-HtmlHelperExtensions 'TestCoordinator.Web.Custom.HtmlHelperExtensions')
  - [EnumDropDownFor\`\`2(htmlHelper,expression,selectedValue,htmlAttributes)](#M-TestCoordinator-Web-Custom-HtmlHelperExtensions-EnumDropDownFor``2-System-Web-Mvc-HtmlHelper{``0},System-Linq-Expressions-Expression{System-Func{``0,``1}},System-Int32,System-Object- 'TestCoordinator.Web.Custom.HtmlHelperExtensions.EnumDropDownFor``2(System.Web.Mvc.HtmlHelper{``0},System.Linq.Expressions.Expression{System.Func{``0,``1}},System.Int32,System.Object)')
  - [GetCurrentActionName(htmlHelper)](#M-TestCoordinator-Web-Custom-HtmlHelperExtensions-GetCurrentActionName-System-Web-Mvc-HtmlHelper- 'TestCoordinator.Web.Custom.HtmlHelperExtensions.GetCurrentActionName(System.Web.Mvc.HtmlHelper)')
  - [GetCurrentControllerName(htmlHelper)](#M-TestCoordinator-Web-Custom-HtmlHelperExtensions-GetCurrentControllerName-System-Web-Mvc-HtmlHelper- 'TestCoordinator.Web.Custom.HtmlHelperExtensions.GetCurrentControllerName(System.Web.Mvc.HtmlHelper)')
  - [JsonSerialize(htmlHelper,value)](#M-TestCoordinator-Web-Custom-HtmlHelperExtensions-JsonSerialize-System-Web-Mvc-HtmlHelper,System-Object- 'TestCoordinator.Web.Custom.HtmlHelperExtensions.JsonSerialize(System.Web.Mvc.HtmlHelper,System.Object)')
- [IHaveCustomMappings](#T-TestCoordinator-Web-ViewModels-IHaveCustomMappings 'TestCoordinator.Web.ViewModels.IHaveCustomMappings')
  - [CreateMappings(configuration)](#M-TestCoordinator-Web-ViewModels-IHaveCustomMappings-CreateMappings-AutoMapper-IConfiguration- 'TestCoordinator.Web.ViewModels.IHaveCustomMappings.CreateMappings(AutoMapper.IConfiguration)')
- [IMapFrom\`1](#T-TestCoordinator-Web-ViewModels-IMapFrom`1 'TestCoordinator.Web.ViewModels.IMapFrom`1')
- [IViewModel\`1](#T-TestCoordinator-Web-ViewModels-IViewModel`1 'TestCoordinator.Web.ViewModels.IViewModel`1')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-IViewModel`1-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.IViewModel`1.ChildTypeDisplayName')
  - [ChildrenCount](#P-TestCoordinator-Web-ViewModels-IViewModel`1-ChildrenCount 'TestCoordinator.Web.ViewModels.IViewModel`1.ChildrenCount')
  - [DateCreated](#P-TestCoordinator-Web-ViewModels-IViewModel`1-DateCreated 'TestCoordinator.Web.ViewModels.IViewModel`1.DateCreated')
  - [Description](#P-TestCoordinator-Web-ViewModels-IViewModel`1-Description 'TestCoordinator.Web.ViewModels.IViewModel`1.Description')
  - [Id](#P-TestCoordinator-Web-ViewModels-IViewModel`1-Id 'TestCoordinator.Web.ViewModels.IViewModel`1.Id')
  - [LastModified](#P-TestCoordinator-Web-ViewModels-IViewModel`1-LastModified 'TestCoordinator.Web.ViewModels.IViewModel`1.LastModified')
  - [ParentId](#P-TestCoordinator-Web-ViewModels-IViewModel`1-ParentId 'TestCoordinator.Web.ViewModels.IViewModel`1.ParentId')
  - [ParentTitle](#P-TestCoordinator-Web-ViewModels-IViewModel`1-ParentTitle 'TestCoordinator.Web.ViewModels.IViewModel`1.ParentTitle')
  - [Title](#P-TestCoordinator-Web-ViewModels-IViewModel`1-Title 'TestCoordinator.Web.ViewModels.IViewModel`1.Title')
- [MvcApplication](#T-TestCoordinator-Web-MvcApplication 'TestCoordinator.Web.MvcApplication')
  - [Application_Start()](#M-TestCoordinator-Web-MvcApplication-Application_Start 'TestCoordinator.Web.MvcApplication.Application_Start')
- [Node](#T-TestCoordinator-Web-Models-Node 'TestCoordinator.Web.Models.Node')
  - [ItemClass](#P-TestCoordinator-Web-Models-Node-ItemClass 'TestCoordinator.Web.Models.Node.ItemClass')
  - [ParentItemChildrenUrlFormat](#P-TestCoordinator-Web-Models-Node-ParentItemChildrenUrlFormat 'TestCoordinator.Web.Models.Node.ParentItemChildrenUrlFormat')
  - [ParentItemId](#P-TestCoordinator-Web-Models-Node-ParentItemId 'TestCoordinator.Web.Models.Node.ParentItemId')
  - [ParentItemTitle](#P-TestCoordinator-Web-Models-Node-ParentItemTitle 'TestCoordinator.Web.Models.Node.ParentItemTitle')
  - [Equals(obj)](#M-TestCoordinator-Web-Models-Node-Equals-System-Object- 'TestCoordinator.Web.Models.Node.Equals(System.Object)')
  - [GetHashCode()](#M-TestCoordinator-Web-Models-Node-GetHashCode 'TestCoordinator.Web.Models.Node.GetHashCode')
- [ProductViewModel](#T-TestCoordinator-Web-ViewModels-ProductViewModel 'TestCoordinator.Web.ViewModels.ProductViewModel')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-ProductViewModel-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.ProductViewModel.ChildTypeDisplayName')
  - [CreateMappings(configuration)](#M-TestCoordinator-Web-ViewModels-ProductViewModel-CreateMappings-AutoMapper-IConfiguration- 'TestCoordinator.Web.ViewModels.ProductViewModel.CreateMappings(AutoMapper.IConfiguration)')
- [ProductsController](#T-TestCoordinator-Web-Controllers-ProductsController 'TestCoordinator.Web.Controllers.ProductsController')
  - [#ctor()](#M-TestCoordinator-Web-Controllers-ProductsController-#ctor 'TestCoordinator.Web.Controllers.ProductsController.#ctor')
  - [BuildBreadcrumb(parentId)](#M-TestCoordinator-Web-Controllers-ProductsController-BuildBreadcrumb-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.ProductsController.BuildBreadcrumb(System.Nullable{System.Int32})')
  - [Create(viewModel,parentId)](#M-TestCoordinator-Web-Controllers-ProductsController-Create-TestCoordinator-Web-ViewModels-ProductViewModel,System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.ProductsController.Create(TestCoordinator.Web.ViewModels.ProductViewModel,System.Nullable{System.Int32})')
- [RegressionTestingController](#T-TestCoordinator-Web-Controllers-RegressionTestingController 'TestCoordinator.Web.Controllers.RegressionTestingController')
  - [Index()](#M-TestCoordinator-Web-Controllers-RegressionTestingController-Index 'TestCoordinator.Web.Controllers.RegressionTestingController.Index')
  - [Start()](#M-TestCoordinator-Web-Controllers-RegressionTestingController-Start 'TestCoordinator.Web.Controllers.RegressionTestingController.Start')
- [RouteConfig](#T-TestCoordinator-Web-Configurations-RouteConfig 'TestCoordinator.Web.Configurations.RouteConfig')
  - [RegisterRoutes(routes)](#M-TestCoordinator-Web-Configurations-RouteConfig-RegisterRoutes-System-Web-Routing-RouteCollection- 'TestCoordinator.Web.Configurations.RouteConfig.RegisterRoutes(System.Web.Routing.RouteCollection)')
- [SearchController](#T-TestCoordinator-Web-Controllers-SearchController 'TestCoordinator.Web.Controllers.SearchController')
  - [UnitOfWork](#P-TestCoordinator-Web-Controllers-SearchController-UnitOfWork 'TestCoordinator.Web.Controllers.SearchController.UnitOfWork')
  - [ByTitle(query)](#M-TestCoordinator-Web-Controllers-SearchController-ByTitle-System-String- 'TestCoordinator.Web.Controllers.SearchController.ByTitle(System.String)')
- [SearchResultViewModel](#T-TestCoordinator-Web-ViewModels-SearchResultViewModel 'TestCoordinator.Web.ViewModels.SearchResultViewModel')
  - [ChildItemsControllerName](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-ChildItemsControllerName 'TestCoordinator.Web.ViewModels.SearchResultViewModel.ChildItemsControllerName')
  - [ControllerName](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-ControllerName 'TestCoordinator.Web.ViewModels.SearchResultViewModel.ControllerName')
  - [Id](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Id 'TestCoordinator.Web.ViewModels.SearchResultViewModel.Id')
  - [SystemType](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-SystemType 'TestCoordinator.Web.ViewModels.SearchResultViewModel.SystemType')
  - [Title](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Title 'TestCoordinator.Web.ViewModels.SearchResultViewModel.Title')
  - [Type](#P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Type 'TestCoordinator.Web.ViewModels.SearchResultViewModel.Type')
- [SortOptionsSelectItems](#T-TestCoordinator-Web-Resources-SortOptionsSelectItems 'TestCoordinator.Web.Resources.SortOptionsSelectItems')
  - [GetDefault()](#M-TestCoordinator-Web-Resources-SortOptionsSelectItems-GetDefault 'TestCoordinator.Web.Resources.SortOptionsSelectItems.GetDefault')
- [StatisticsController](#T-TestCoordinator-Web-Controllers-StatisticsController 'TestCoordinator.Web.Controllers.StatisticsController')
  - [#ctor()](#M-TestCoordinator-Web-Controllers-StatisticsController-#ctor 'TestCoordinator.Web.Controllers.StatisticsController.#ctor')
  - [AllProducts()](#M-TestCoordinator-Web-Controllers-StatisticsController-AllProducts 'TestCoordinator.Web.Controllers.StatisticsController.AllProducts')
  - [General()](#M-TestCoordinator-Web-Controllers-StatisticsController-General 'TestCoordinator.Web.Controllers.StatisticsController.General')
  - [Index()](#M-TestCoordinator-Web-Controllers-StatisticsController-Index 'TestCoordinator.Web.Controllers.StatisticsController.Index')
  - [Product(id)](#M-TestCoordinator-Web-Controllers-StatisticsController-Product-System-Int32- 'TestCoordinator.Web.Controllers.StatisticsController.Product(System.Int32)')
- [StatisticsViewModel](#T-TestCoordinator-Web-ViewModels-StatisticsViewModel 'TestCoordinator.Web.ViewModels.StatisticsViewModel')
  - [AreasCount](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-AreasCount 'TestCoordinator.Web.ViewModels.StatisticsViewModel.AreasCount')
  - [AutomationChartData](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-AutomationChartData 'TestCoordinator.Web.ViewModels.StatisticsViewModel.AutomationChartData')
  - [FeaturesCount](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-FeaturesCount 'TestCoordinator.Web.ViewModels.StatisticsViewModel.FeaturesCount')
  - [ProductsCount](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-ProductsCount 'TestCoordinator.Web.ViewModels.StatisticsViewModel.ProductsCount')
  - [StatusesChartData](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-StatusesChartData 'TestCoordinator.Web.ViewModels.StatisticsViewModel.StatusesChartData')
  - [TestCases](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-TestCases 'TestCoordinator.Web.ViewModels.StatisticsViewModel.TestCases')
  - [TestCasesCount](#P-TestCoordinator-Web-ViewModels-StatisticsViewModel-TestCasesCount 'TestCoordinator.Web.ViewModels.StatisticsViewModel.TestCasesCount')
- [TestCaseViewModel](#T-TestCoordinator-Web-ViewModels-TestCaseViewModel 'TestCoordinator.Web.ViewModels.TestCaseViewModel')
  - [Attachments](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Attachments 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Attachments')
  - [Automated](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Automated 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Automated')
  - [AutomatedTests](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-AutomatedTests 'TestCoordinator.Web.ViewModels.TestCaseViewModel.AutomatedTests')
  - [Bugs](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Bugs 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Bugs')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.TestCaseViewModel.ChildTypeDisplayName')
  - [Environment](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Environment 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Environment')
  - [Given](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Given 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Given')
  - [Priority](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Priority 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Priority')
  - [ProductVersion](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-ProductVersion 'TestCoordinator.Web.ViewModels.TestCaseViewModel.ProductVersion')
  - [Status](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Status 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Status')
  - [Then](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Then 'TestCoordinator.Web.ViewModels.TestCaseViewModel.Then')
  - [When](#P-TestCoordinator-Web-ViewModels-TestCaseViewModel-When 'TestCoordinator.Web.ViewModels.TestCaseViewModel.When')
  - [CreateMappings(configuration)](#M-TestCoordinator-Web-ViewModels-TestCaseViewModel-CreateMappings-AutoMapper-IConfiguration- 'TestCoordinator.Web.ViewModels.TestCaseViewModel.CreateMappings(AutoMapper.IConfiguration)')
- [TestCasesController](#T-TestCoordinator-Web-Controllers-TestCasesController 'TestCoordinator.Web.Controllers.TestCasesController')
  - [#ctor()](#M-TestCoordinator-Web-Controllers-TestCasesController-#ctor 'TestCoordinator.Web.Controllers.TestCasesController.#ctor')
  - [BuildBreadcrumb(parentId)](#M-TestCoordinator-Web-Controllers-TestCasesController-BuildBreadcrumb-System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.TestCasesController.BuildBreadcrumb(System.Nullable{System.Int32})')
  - [Create(viewModel,parentId)](#M-TestCoordinator-Web-Controllers-TestCasesController-Create-TestCoordinator-Web-ViewModels-TestCaseViewModel,System-Nullable{System-Int32}- 'TestCoordinator.Web.Controllers.TestCasesController.Create(TestCoordinator.Web.ViewModels.TestCaseViewModel,System.Nullable{System.Int32})')
- [ViewDataDictionaryExtensions](#T-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions 'TestCoordinator.Web.Custom.ViewDataDictionaryExtensions')
  - [Add(viewDataDictionary,key,value)](#M-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions-Add-System-Web-Mvc-ViewDataDictionary,TestCoordinator-Web-Resources-ViewDataKeys,System-Object- 'TestCoordinator.Web.Custom.ViewDataDictionaryExtensions.Add(System.Web.Mvc.ViewDataDictionary,TestCoordinator.Web.Resources.ViewDataKeys,System.Object)')
  - [Get\`\`1(viewDataDictionary,key)](#M-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions-Get``1-System-Web-Mvc-ViewDataDictionary,TestCoordinator-Web-Resources-ViewDataKeys- 'TestCoordinator.Web.Custom.ViewDataDictionaryExtensions.Get``1(System.Web.Mvc.ViewDataDictionary,TestCoordinator.Web.Resources.ViewDataKeys)')
- [ViewDataKeys](#T-TestCoordinator-Web-Resources-ViewDataKeys 'TestCoordinator.Web.Resources.ViewDataKeys')
  - [Action](#F-TestCoordinator-Web-Resources-ViewDataKeys-Action 'TestCoordinator.Web.Resources.ViewDataKeys.Action')
  - [Breadcrumb](#F-TestCoordinator-Web-Resources-ViewDataKeys-Breadcrumb 'TestCoordinator.Web.Resources.ViewDataKeys.Breadcrumb')
  - [ChildItemsRouteFormat](#F-TestCoordinator-Web-Resources-ViewDataKeys-ChildItemsRouteFormat 'TestCoordinator.Web.Resources.ViewDataKeys.ChildItemsRouteFormat')
  - [CurrentTypeDisplayNameInPlural](#F-TestCoordinator-Web-Resources-ViewDataKeys-CurrentTypeDisplayNameInPlural 'TestCoordinator.Web.Resources.ViewDataKeys.CurrentTypeDisplayNameInPlural')
  - [CurrentTypeDisplayNameInSingular](#F-TestCoordinator-Web-Resources-ViewDataKeys-CurrentTypeDisplayNameInSingular 'TestCoordinator.Web.Resources.ViewDataKeys.CurrentTypeDisplayNameInSingular')
  - [FilterOptions](#F-TestCoordinator-Web-Resources-ViewDataKeys-FilterOptions 'TestCoordinator.Web.Resources.ViewDataKeys.FilterOptions')
  - [SortOptions](#F-TestCoordinator-Web-Resources-ViewDataKeys-SortOptions 'TestCoordinator.Web.Resources.ViewDataKeys.SortOptions')
  - [Title](#F-TestCoordinator-Web-Resources-ViewDataKeys-Title 'TestCoordinator.Web.Resources.ViewDataKeys.Title')
- [ViewModelBase\`1](#T-TestCoordinator-Web-ViewModels-ViewModelBase`1 'TestCoordinator.Web.ViewModels.ViewModelBase`1')
  - [ChildTypeDisplayName](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ChildTypeDisplayName 'TestCoordinator.Web.ViewModels.ViewModelBase`1.ChildTypeDisplayName')
  - [ChildrenCount](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ChildrenCount 'TestCoordinator.Web.ViewModels.ViewModelBase`1.ChildrenCount')
  - [DateCreated](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-DateCreated 'TestCoordinator.Web.ViewModels.ViewModelBase`1.DateCreated')
  - [Description](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Description 'TestCoordinator.Web.ViewModels.ViewModelBase`1.Description')
  - [Id](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Id 'TestCoordinator.Web.ViewModels.ViewModelBase`1.Id')
  - [LastModified](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-LastModified 'TestCoordinator.Web.ViewModels.ViewModelBase`1.LastModified')
  - [ParentId](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ParentId 'TestCoordinator.Web.ViewModels.ViewModelBase`1.ParentId')
  - [ParentTitle](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ParentTitle 'TestCoordinator.Web.ViewModels.ViewModelBase`1.ParentTitle')
  - [Title](#P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Title 'TestCoordinator.Web.ViewModels.ViewModelBase`1.Title')
  - [Equals(obj)](#M-TestCoordinator-Web-ViewModels-ViewModelBase`1-Equals-System-Object- 'TestCoordinator.Web.ViewModels.ViewModelBase`1.Equals(System.Object)')
  - [GetHashCode()](#M-TestCoordinator-Web-ViewModels-ViewModelBase`1-GetHashCode 'TestCoordinator.Web.ViewModels.ViewModelBase`1.GetHashCode')
- [ViewNames](#T-TestCoordinator-Web-Resources-ViewNames 'TestCoordinator.Web.Resources.ViewNames')
  - [AttachmentPartial](#F-TestCoordinator-Web-Resources-ViewNames-AttachmentPartial 'TestCoordinator.Web.Resources.ViewNames.AttachmentPartial')
  - [AutomatedTestPartial](#F-TestCoordinator-Web-Resources-ViewNames-AutomatedTestPartial 'TestCoordinator.Web.Resources.ViewNames.AutomatedTestPartial')
  - [AutomatedTestsPartial](#F-TestCoordinator-Web-Resources-ViewNames-AutomatedTestsPartial 'TestCoordinator.Web.Resources.ViewNames.AutomatedTestsPartial')
  - [BreadcrumbPartial](#F-TestCoordinator-Web-Resources-ViewNames-BreadcrumbPartial 'TestCoordinator.Web.Resources.ViewNames.BreadcrumbPartial')
  - [BugPartial](#F-TestCoordinator-Web-Resources-ViewNames-BugPartial 'TestCoordinator.Web.Resources.ViewNames.BugPartial')
  - [BugsPartial](#F-TestCoordinator-Web-Resources-ViewNames-BugsPartial 'TestCoordinator.Web.Resources.ViewNames.BugsPartial')
  - [DeleteConfirmationDialogPartial](#F-TestCoordinator-Web-Resources-ViewNames-DeleteConfirmationDialogPartial 'TestCoordinator.Web.Resources.ViewNames.DeleteConfirmationDialogPartial')
  - [GeneralStatisticsPartial](#F-TestCoordinator-Web-Resources-ViewNames-GeneralStatisticsPartial 'TestCoordinator.Web.Resources.ViewNames.GeneralStatisticsPartial')
  - [Index](#F-TestCoordinator-Web-Resources-ViewNames-Index 'TestCoordinator.Web.Resources.ViewNames.Index')
  - [ItemDetailsFormPartial](#F-TestCoordinator-Web-Resources-ViewNames-ItemDetailsFormPartial 'TestCoordinator.Web.Resources.ViewNames.ItemDetailsFormPartial')
  - [ItemLocked](#F-TestCoordinator-Web-Resources-ViewNames-ItemLocked 'TestCoordinator.Web.Resources.ViewNames.ItemLocked')
  - [Items](#F-TestCoordinator-Web-Resources-ViewNames-Items 'TestCoordinator.Web.Resources.ViewNames.Items')
  - [ItemsPartial](#F-TestCoordinator-Web-Resources-ViewNames-ItemsPartial 'TestCoordinator.Web.Resources.ViewNames.ItemsPartial')
  - [ManageAutomatedTestsDialogPartial](#F-TestCoordinator-Web-Resources-ViewNames-ManageAutomatedTestsDialogPartial 'TestCoordinator.Web.Resources.ViewNames.ManageAutomatedTestsDialogPartial')
  - [ManageBugsDialogPartial](#F-TestCoordinator-Web-Resources-ViewNames-ManageBugsDialogPartial 'TestCoordinator.Web.Resources.ViewNames.ManageBugsDialogPartial')
  - [NoItems](#F-TestCoordinator-Web-Resources-ViewNames-NoItems 'TestCoordinator.Web.Resources.ViewNames.NoItems')
  - [SearchResultsPartial](#F-TestCoordinator-Web-Resources-ViewNames-SearchResultsPartial 'TestCoordinator.Web.Resources.ViewNames.SearchResultsPartial')
  - [StatisticsChartsPartial](#F-TestCoordinator-Web-Resources-ViewNames-StatisticsChartsPartial 'TestCoordinator.Web.Resources.ViewNames.StatisticsChartsPartial')
  - [TestCasePartial](#F-TestCoordinator-Web-Resources-ViewNames-TestCasePartial 'TestCoordinator.Web.Resources.ViewNames.TestCasePartial')
- [WebApiConfig](#T-TestCoordinator-Web-Configurations-WebApiConfig 'TestCoordinator.Web.Configurations.WebApiConfig')
  - [Register(config)](#M-TestCoordinator-Web-Configurations-WebApiConfig-Register-System-Web-Http-HttpConfiguration- 'TestCoordinator.Web.Configurations.WebApiConfig.Register(System.Web.Http.HttpConfiguration)')

<a name='T-TestCoordinator-Web-Resources-ActionNames'></a>
## ActionNames `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Denotes different action names.

<a name='F-TestCoordinator-Web-Resources-ActionNames-CancelEditing'></a>
### CancelEditing `constants`

##### Summary

The cancel editing action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Create'></a>
### Create `constants`

##### Summary

The create action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Delete'></a>
### Delete `constants`

##### Summary

The delete action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Download'></a>
### Download `constants`

##### Summary

The download action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Edit'></a>
### Edit `constants`

##### Summary

The edit action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-General'></a>
### General `constants`

##### Summary

The general action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Index'></a>
### Index `constants`

##### Summary

The index action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Items'></a>
### Items `constants`

##### Summary

The items action name

<a name='F-TestCoordinator-Web-Resources-ActionNames-Start'></a>
### Start `constants`

##### Summary

The start action name

<a name='T-TestCoordinator-Web-ViewModels-AreaViewModel'></a>
## AreaViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Area ViewModel.

<a name='P-TestCoordinator-Web-ViewModels-AreaViewModel-Assignee'></a>
### Assignee `property`

##### Summary

Gets or sets the assignee.

<a name='P-TestCoordinator-Web-ViewModels-AreaViewModel-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='P-TestCoordinator-Web-ViewModels-AreaViewModel-Priority'></a>
### Priority `property`

##### Summary

Gets or sets the priority.

<a name='M-TestCoordinator-Web-ViewModels-AreaViewModel-CreateMappings-AutoMapper-IConfiguration-'></a>
### CreateMappings(configuration) `method`

##### Summary

Creates the mappings.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| configuration | [AutoMapper.IConfiguration](#T-AutoMapper-IConfiguration 'AutoMapper.IConfiguration') | The configuration. |

<a name='T-TestCoordinator-Web-Controllers-AreasController'></a>
## AreasController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for Areas related requests and operations.

<a name='M-TestCoordinator-Web-Controllers-AreasController-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [AreasController](#T-TestCoordinator-Web-Controllers-AreasController 'TestCoordinator.Web.Controllers.AreasController') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Web-Controllers-AreasController-BuildBreadcrumb-System-Nullable{System-Int32}-'></a>
### BuildBreadcrumb(parentId) `method`

##### Summary

Builds the breadcrumb.

##### Returns

The breadcrumb.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Web-Controllers-AreasController-Create-TestCoordinator-Web-ViewModels-AreaViewModel,System-Nullable{System-Int32}-'></a>
### Create(viewModel,parentId) `method`

##### Summary

Creates the item from the specified view model.

##### Returns

Redirects to all items once Create operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [TestCoordinator.Web.ViewModels.AreaViewModel](#T-TestCoordinator-Web-ViewModels-AreaViewModel 'TestCoordinator.Web.ViewModels.AreaViewModel') | The view model. |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='T-TestCoordinator-Web-ViewModels-AttachmentViewModel'></a>
## AttachmentViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for attachments.

<a name='P-TestCoordinator-Web-ViewModels-AttachmentViewModel-FileName'></a>
### FileName `property`

##### Summary

Gets or sets the name of the file.

<a name='P-TestCoordinator-Web-ViewModels-AttachmentViewModel-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='T-TestCoordinator-Web-Controllers-AttachmentsController'></a>
## AttachmentsController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Attachments controller.

##### See Also

- [System.Web.Mvc.Controller](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.Controller 'System.Web.Mvc.Controller')

<a name='P-TestCoordinator-Web-Controllers-AttachmentsController-UnitOfWork'></a>
### UnitOfWork `property`

##### Summary

Gets the unit of work.

<a name='M-TestCoordinator-Web-Controllers-AttachmentsController-Delete-System-Guid-'></a>
### Delete(id) `method`

##### Summary

Deletes an attachment.

##### Returns

EmptyResult - denotes successful removal.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Guid](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Guid 'System.Guid') | The attachment identifier. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.IO.FileNotFoundException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.IO.FileNotFoundException 'System.IO.FileNotFoundException') | File not found. |

<a name='M-TestCoordinator-Web-Controllers-AttachmentsController-DeleteAll'></a>
### DeleteAll() `method`

##### Summary

Deletes all attachments from the database and the disk.

##### Returns

Redirects to home screen if operation is successful.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-AttachmentsController-Download-System-Guid-'></a>
### Download(id) `method`

##### Summary

Downloads an attachment.

##### Returns

The requested attachment.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Guid](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Guid 'System.Guid') | The attachment identifier. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.IO.FileNotFoundException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.IO.FileNotFoundException 'System.IO.FileNotFoundException') | File not found. |

<a name='M-TestCoordinator-Web-Controllers-AttachmentsController-FileUpload'></a>
### FileUpload() `method`

##### Summary

Uploads a file.

##### Returns

Partial view with the attachment item.

##### Parameters

This method has no parameters.

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.Exception](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Exception 'System.Exception') | File is empty. |

<a name='T-TestCoordinator-Web-Resources-AttributeNames'></a>
## AttributeNames `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Resources class for names of attributes

<a name='F-TestCoordinator-Web-Resources-AttributeNames-Name'></a>
### Name `constants`

##### Summary

The name attribute

<a name='T-TestCoordinator-Web-Configurations-AutoMapperConfig'></a>
## AutoMapperConfig `type`

##### Namespace

TestCoordinator.Web.Configurations

##### Summary

AutoMapper configuration.

<a name='M-TestCoordinator-Web-Configurations-AutoMapperConfig-RegisterMappings'></a>
### RegisterMappings() `method`

##### Summary

Registers the mappings.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-ViewModels-AutomatedTestViewModel'></a>
## AutomatedTestViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for automated tests.

<a name='P-TestCoordinator-Web-ViewModels-AutomatedTestViewModel-Fixture'></a>
### Fixture `property`

##### Summary

Gets or sets the fixture.

<a name='P-TestCoordinator-Web-ViewModels-AutomatedTestViewModel-TestName'></a>
### TestName `property`

##### Summary

Gets or sets the name of the test.

<a name='T-TestCoordinator-Web-Controllers-AutomatedTestsController'></a>
## AutomatedTestsController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

The controller for automated tests.

##### See Also

- [System.Web.Mvc.Controller](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.Controller 'System.Web.Mvc.Controller')

<a name='M-TestCoordinator-Web-Controllers-AutomatedTestsController-GetManageScreen-System-String-'></a>
### GetManageScreen(automatedTests) `method`

##### Summary

Gets the automated tests manage screen.

##### Returns

The manage screen partial view for automated tests.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| automatedTests | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The automated tests. |

<a name='M-TestCoordinator-Web-Controllers-AutomatedTestsController-NewTest'></a>
### NewTest() `method`

##### Summary

New automated test contents.

##### Returns

Partial view for an automated test.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Models-Breadcrumb'></a>
## Breadcrumb `type`

##### Namespace

TestCoordinator.Web.Models

##### Summary

The model used for the breadcrumb navigation

<a name='M-TestCoordinator-Web-Models-Breadcrumb-#ctor-TestCoordinator-Web-Models-Node[]-'></a>
### #ctor(nodes) `constructor`

##### Summary

Initializes a new instance of the [Breadcrumb](#T-TestCoordinator-Web-Models-Breadcrumb 'TestCoordinator.Web.Models.Breadcrumb') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| nodes | [TestCoordinator.Web.Models.Node[]](#T-TestCoordinator-Web-Models-Node[] 'TestCoordinator.Web.Models.Node[]') | The nodes. |

<a name='M-TestCoordinator-Web-Models-Breadcrumb-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [Breadcrumb](#T-TestCoordinator-Web-Models-Breadcrumb 'TestCoordinator.Web.Models.Breadcrumb') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Web-Models-Breadcrumb-Nodes'></a>
### Nodes `property`

##### Summary

Gets the nodes.

<a name='M-TestCoordinator-Web-Models-Breadcrumb-AddNode-TestCoordinator-Web-Models-Node-'></a>
### AddNode(node) `method`

##### Summary

Adds the node.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| node | [TestCoordinator.Web.Models.Node](#T-TestCoordinator-Web-Models-Node 'TestCoordinator.Web.Models.Node') | The node. |

<a name='M-TestCoordinator-Web-Models-Breadcrumb-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Determines whether the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object'), is equal to this instance.

##### Returns

`true` if the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') is equal to this instance; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') to compare with this instance. |

<a name='M-TestCoordinator-Web-Models-Breadcrumb-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

Returns a hash code for this instance.

##### Returns

A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-ViewModels-BugViewModel'></a>
## BugViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for bugs.

<a name='P-TestCoordinator-Web-ViewModels-BugViewModel-BugTrackingSystemItemUrl'></a>
### BugTrackingSystemItemUrl `property`

##### Summary

Gets or sets the bug tracking system item URL.

<a name='P-TestCoordinator-Web-ViewModels-BugViewModel-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='T-TestCoordinator-Web-Controllers-BugsController'></a>
## BugsController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

The Bugs controller.

##### See Also

- [System.Web.Mvc.Controller](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.Controller 'System.Web.Mvc.Controller')

<a name='M-TestCoordinator-Web-Controllers-BugsController-GetManageScreen-System-String-'></a>
### GetManageScreen(bugs) `method`

##### Summary

Gets the bugs manage screen.

##### Returns

The manage screen partial view for bugs.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bugs | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The bugs. |

<a name='M-TestCoordinator-Web-Controllers-BugsController-NewBug'></a>
### NewBug() `method`

##### Summary

New bug contents.

##### Returns

Partial view for a bug.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Configurations-BundleConfig'></a>
## BundleConfig `type`

##### Namespace

TestCoordinator.Web.Configurations

##### Summary

Bundle configuration.

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-BootstrapScriptsBundlePath'></a>
### BootstrapScriptsBundlePath `constants`

##### Summary

The bootstrap scripts bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-BootstrapStylesBundlePath'></a>
### BootstrapStylesBundlePath `constants`

##### Summary

The bootstrap styles bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-ChartJsScriptsBundlePath'></a>
### ChartJsScriptsBundlePath `constants`

##### Summary

The external chart library scripts bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-DataTablesScriptsBundlePath'></a>
### DataTablesScriptsBundlePath `constants`

##### Summary

The data tables scripts bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-DataTablesStylesBundlePath'></a>
### DataTablesStylesBundlePath `constants`

##### Summary

The data tables styles bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-HideSideSectionsBundlePath'></a>
### HideSideSectionsBundlePath `constants`

##### Summary

The hide side sections bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-JQueryBundlePath'></a>
### JQueryBundlePath `constants`

##### Summary

The jQuery bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-JQueryFileUploadScriptsBundlePath'></a>
### JQueryFileUploadScriptsBundlePath `constants`

##### Summary

The jQuery file upload scripts bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-JQueryFileUploadStylesBundlePath'></a>
### JQueryFileUploadStylesBundlePath `constants`

##### Summary

The jQuery file upload styles bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-JQueryValidationBundlePath'></a>
### JQueryValidationBundlePath `constants`

##### Summary

The jQuery validation bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-SiteScriptsPath'></a>
### SiteScriptsPath `constants`

##### Summary

The site scripts path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-SiteStylesPath'></a>
### SiteStylesPath `constants`

##### Summary

The site styles path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-TestCasesScriptsBundlePath'></a>
### TestCasesScriptsBundlePath `constants`

##### Summary

The test cases scripts bundle path

<a name='F-TestCoordinator-Web-Configurations-BundleConfig-TinyMceEditorScriptsPath'></a>
### TinyMceEditorScriptsPath `constants`

##### Summary

The external editor library scripts path

<a name='M-TestCoordinator-Web-Configurations-BundleConfig-RegisterBundles-System-Web-Optimization-BundleCollection-'></a>
### RegisterBundles(bundles) `method`

##### Summary

Registers the bundles.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bundles | [System.Web.Optimization.BundleCollection](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Optimization.BundleCollection 'System.Web.Optimization.BundleCollection') | The bundles. |

<a name='T-TestCoordinator-Web-ViewModels-ChartItemViewModel'></a>
## ChartItemViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for chart items

<a name='P-TestCoordinator-Web-ViewModels-ChartItemViewModel-HexColor'></a>
### HexColor `property`

##### Summary

Gets or sets the color of the hexadecimal.

<a name='P-TestCoordinator-Web-ViewModels-ChartItemViewModel-Label'></a>
### Label `property`

##### Summary

Gets or sets the label.

<a name='P-TestCoordinator-Web-ViewModels-ChartItemViewModel-Value'></a>
### Value `property`

##### Summary

Gets or sets the value.

<a name='T-TestCoordinator-Web-Controllers-ControllerBase`2'></a>
## ControllerBase\`2 `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

The base controller for generic operations in the system.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TModel | The type of the model. |
| TViewModel | The type of the view model. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-#ctor-`1-'></a>
### #ctor(viewModel) `constructor`

##### Summary

Initializes a new instance of the [ControllerBase\`2](#T-TestCoordinator-Web-Controllers-ControllerBase`2 'TestCoordinator.Web.Controllers.ControllerBase`2') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [\`1](#T-`1 '`1') | The view model. |

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the load child items URL format.

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-CurrentTypeDisplayNameInPlural'></a>
### CurrentTypeDisplayNameInPlural `property`

##### Summary

Gets the current type display name in plural.

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-CurrentTypeDisplayNameInSingular'></a>
### CurrentTypeDisplayNameInSingular `property`

##### Summary

Gets the current type display name in singular.

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-StringResources'></a>
### StringResources `property`

##### Summary

Gets the string resources.

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-UnitOfWork'></a>
### UnitOfWork `property`

##### Summary

Gets the unit of work.

<a name='P-TestCoordinator-Web-Controllers-ControllerBase`2-ViewModel'></a>
### ViewModel `property`

##### Summary

Gets the view model.

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-BuildBreadcrumb-System-Nullable{System-Int32}-'></a>
### BuildBreadcrumb(parentId) `method`

##### Summary

Builds the breadcrumb.

##### Returns

The breadcrumb.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-CancelEditing-`1-'></a>
### CancelEditing(viewModel) `method`

##### Summary

Cancels the editing.

##### Returns

Redirects to all items screen.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [\`1](#T-`1 '`1') | The view model. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Create-`1,System-Nullable{System-Int32}-'></a>
### Create(viewModel,parentId) `method`

##### Summary

Creates the item from the specified view model.

##### Returns

Redirects to all items once Create operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [\`1](#T-`1 '`1') | The view model. |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Create-System-Nullable{System-Int32}-'></a>
### Create(parentId) `method`

##### Summary

Retrieves the view for creating new item.

##### Returns

The create item view.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Delete-System-Int32-'></a>
### Delete(id) `method`

##### Summary

Deletes an item.

##### Returns

Redirects to all items once item is deleted.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The identifier. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Edit-`1-'></a>
### Edit(viewModel) `method`

##### Summary

Edits the item from the specified view model.

##### Returns

Redirects to all items once Edit operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [\`1](#T-`1 '`1') | The view model. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Edit-System-Int32-'></a>
### Edit(id) `method`

##### Summary

Retrieves the view for editing an item.

##### Returns

The edit item view.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The identifier. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Items-System-Nullable{System-Int32},System-String-'></a>
### Items(parentId,sort) `method`

##### Summary

Retrieves all items.

##### Returns

All items view.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |
| sort | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The sort option. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-Items-System-Collections-Generic-IEnumerable{`1}-'></a>
### Items(viewModels) `method`

##### Summary

Retrieves all items.

##### Returns

Either all or no items view.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModels | [System.Collections.Generic.IEnumerable{\`1}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{`1}') | The view models. |

<a name='M-TestCoordinator-Web-Controllers-ControllerBase`2-OnActionExecuted-System-Web-Mvc-ActionExecutedContext-'></a>
### OnActionExecuted(filterContext) `method`

##### Summary

Called after the action method is invoked.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| filterContext | [System.Web.Mvc.ActionExecutedContext](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.ActionExecutedContext 'System.Web.Mvc.ActionExecutedContext') | Information about the current request and action. |

<a name='T-TestCoordinator-Web-Resources-ControllerNames'></a>
## ControllerNames `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Specifies different controller names.

<a name='F-TestCoordinator-Web-Resources-ControllerNames-Attachments'></a>
### Attachments `constants`

##### Summary

The attachments controller name

<a name='F-TestCoordinator-Web-Resources-ControllerNames-Error'></a>
### Error `constants`

##### Summary

The error controller name

<a name='F-TestCoordinator-Web-Resources-ControllerNames-Products'></a>
### Products `constants`

##### Summary

The products controller name

<a name='F-TestCoordinator-Web-Resources-ControllerNames-RegressionTesting'></a>
### RegressionTesting `constants`

##### Summary

The regression testing controller name

<a name='F-TestCoordinator-Web-Resources-ControllerNames-Statistics'></a>
### Statistics `constants`

##### Summary

The statistics controller name

<a name='T-TestCoordinator-Web-Custom-CustomSelectListItem'></a>
## CustomSelectListItem `type`

##### Namespace

TestCoordinator.Web.Custom

##### Summary

Custom implementation of the SelectListItem

##### See Also

- [System.Web.Mvc.SelectListItem](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.SelectListItem 'System.Web.Mvc.SelectListItem')

<a name='M-TestCoordinator-Web-Custom-CustomSelectListItem-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Determines whether the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object'), is equal to this instance.

##### Returns

`true` if the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') is equal to this instance; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') to compare with this instance. |

<a name='M-TestCoordinator-Web-Custom-CustomSelectListItem-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

Returns a hash code for this instance.

##### Returns

A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Controllers-DemoDataController'></a>
## DemoDataController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Controller used for dummy data generation of entities to ease testing.

<a name='P-TestCoordinator-Web-Controllers-DemoDataController-UnitOfWork'></a>
### UnitOfWork `property`

##### Summary

Gets the unit of work.

<a name='M-TestCoordinator-Web-Controllers-DemoDataController-Cleanup'></a>
### Cleanup() `method`

##### Summary

Cleans up all the data from the system.

##### Returns

Redirects to all products.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-DemoDataController-Generate'></a>
### Generate() `method`

##### Summary

Generates demo data.

##### Returns

Redirects to all products.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Controllers-ErrorController'></a>
## ErrorController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Controller for handling errors within the application

##### See Also

- [System.Web.Mvc.Controller](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.Controller 'System.Web.Mvc.Controller')

<a name='M-TestCoordinator-Web-Controllers-ErrorController-Index'></a>
### Index() `method`

##### Summary

Action for generic errors.

##### Returns

Generic error view.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-ErrorController-NotFound'></a>
### NotFound() `method`

##### Summary

Action for NotFound (404) error.

##### Returns

Generic error view.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-ViewModels-ErrorViewModel'></a>
## ErrorViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for system error

<a name='P-TestCoordinator-Web-ViewModels-ErrorViewModel-Details'></a>
### Details `property`

##### Summary

Gets or sets the details.

<a name='P-TestCoordinator-Web-ViewModels-ErrorViewModel-Heading'></a>
### Heading `property`

##### Summary

Gets or sets the heading.

<a name='P-TestCoordinator-Web-ViewModels-ErrorViewModel-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='T-TestCoordinator-Web-ViewModels-FeatureViewModel'></a>
## FeatureViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Feature ViewModel.

<a name='P-TestCoordinator-Web-ViewModels-FeatureViewModel-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='M-TestCoordinator-Web-ViewModels-FeatureViewModel-CreateMappings-AutoMapper-IConfiguration-'></a>
### CreateMappings(configuration) `method`

##### Summary

Creates the mappings.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| configuration | [AutoMapper.IConfiguration](#T-AutoMapper-IConfiguration 'AutoMapper.IConfiguration') | The configuration. |

<a name='T-TestCoordinator-Web-Controllers-FeaturesController'></a>
## FeaturesController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for Features related requests and operations.

<a name='M-TestCoordinator-Web-Controllers-FeaturesController-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [FeaturesController](#T-TestCoordinator-Web-Controllers-FeaturesController 'TestCoordinator.Web.Controllers.FeaturesController') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Web-Controllers-FeaturesController-BuildBreadcrumb-System-Nullable{System-Int32}-'></a>
### BuildBreadcrumb(parentId) `method`

##### Summary

Builds the breadcrumb.

##### Returns

The breadcrumb.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Web-Controllers-FeaturesController-Create-TestCoordinator-Web-ViewModels-FeatureViewModel,System-Nullable{System-Int32}-'></a>
### Create(viewModel,parentId) `method`

##### Summary

Creates the item from the specified view model.

##### Returns

Redirects to all items once Create operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [TestCoordinator.Web.ViewModels.FeatureViewModel](#T-TestCoordinator-Web-ViewModels-FeatureViewModel 'TestCoordinator.Web.ViewModels.FeatureViewModel') | The view model. |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='T-TestCoordinator-Web-Configurations-FilterConfig'></a>
## FilterConfig `type`

##### Namespace

TestCoordinator.Web.Configurations

##### Summary

Filter configuration

<a name='M-TestCoordinator-Web-Configurations-FilterConfig-RegisterGlobalFilters-System-Web-Mvc-GlobalFilterCollection-'></a>
### RegisterGlobalFilters(filters) `method`

##### Summary

Registers the global filters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| filters | [System.Web.Mvc.GlobalFilterCollection](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.GlobalFilterCollection 'System.Web.Mvc.GlobalFilterCollection') | The filters. |

<a name='T-TestCoordinator-Web-Custom-HtmlHelperExtensions'></a>
## HtmlHelperExtensions `type`

##### Namespace

TestCoordinator.Web.Custom

##### Summary

Provides access to different HTML helper extensions.

<a name='M-TestCoordinator-Web-Custom-HtmlHelperExtensions-EnumDropDownFor``2-System-Web-Mvc-HtmlHelper{``0},System-Linq-Expressions-Expression{System-Func{``0,``1}},System-Int32,System-Object-'></a>
### EnumDropDownFor\`\`2(htmlHelper,expression,selectedValue,htmlAttributes) `method`

##### Summary

Returns a HTML drop-down for a model enumeration property.

##### Returns

HTML-encoded string.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| htmlHelper | [System.Web.Mvc.HtmlHelper{\`\`0}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.HtmlHelper 'System.Web.Mvc.HtmlHelper{``0}') | The HTML helper. |
| expression | [System.Linq.Expressions.Expression{System.Func{\`\`0,\`\`1}}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Linq.Expressions.Expression 'System.Linq.Expressions.Expression{System.Func{``0,``1}}') | The expression. |
| selectedValue | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The selected value. |
| htmlAttributes | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The HTML attributes. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TModel | The type of the model. |
| TEnum | The type of the enumeration. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentException 'System.ArgumentException') | TValue must be an enumeration. |

<a name='M-TestCoordinator-Web-Custom-HtmlHelperExtensions-GetCurrentActionName-System-Web-Mvc-HtmlHelper-'></a>
### GetCurrentActionName(htmlHelper) `method`

##### Summary

Gets the name of the current action.

##### Returns

The action name.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| htmlHelper | [System.Web.Mvc.HtmlHelper](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.HtmlHelper 'System.Web.Mvc.HtmlHelper') | The HTML helper. |

<a name='M-TestCoordinator-Web-Custom-HtmlHelperExtensions-GetCurrentControllerName-System-Web-Mvc-HtmlHelper-'></a>
### GetCurrentControllerName(htmlHelper) `method`

##### Summary

Gets the name of the current controller.

##### Returns

The controller name.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| htmlHelper | [System.Web.Mvc.HtmlHelper](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.HtmlHelper 'System.Web.Mvc.HtmlHelper') | The HTML helper. |

<a name='M-TestCoordinator-Web-Custom-HtmlHelperExtensions-JsonSerialize-System-Web-Mvc-HtmlHelper,System-Object-'></a>
### JsonSerialize(htmlHelper,value) `method`

##### Summary

Serializes an object using the JavaScripSerializer.

##### Returns

Serialized object value as string.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| htmlHelper | [System.Web.Mvc.HtmlHelper](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.HtmlHelper 'System.Web.Mvc.HtmlHelper') | The HTML helper. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |

<a name='T-TestCoordinator-Web-ViewModels-IHaveCustomMappings'></a>
## IHaveCustomMappings `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Denotes View models with custom mappings.

<a name='M-TestCoordinator-Web-ViewModels-IHaveCustomMappings-CreateMappings-AutoMapper-IConfiguration-'></a>
### CreateMappings(configuration) `method`

##### Summary

Creates the mappings.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| configuration | [AutoMapper.IConfiguration](#T-AutoMapper-IConfiguration 'AutoMapper.IConfiguration') | The configuration. |

<a name='T-TestCoordinator-Web-ViewModels-IMapFrom`1'></a>
## IMapFrom\`1 `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Denotes view models using the AutoMapper.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | Model object type. |

<a name='T-TestCoordinator-Web-ViewModels-IViewModel`1'></a>
## IViewModel\`1 `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Defines base properties of all ViewModels.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | Generic ViewModel type. |

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-ChildrenCount'></a>
### ChildrenCount `property`

##### Summary

Gets or sets the children count.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-DateCreated'></a>
### DateCreated `property`

##### Summary

Gets or sets the date created.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-Description'></a>
### Description `property`

##### Summary

Gets or sets the description.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-LastModified'></a>
### LastModified `property`

##### Summary

Gets or sets the last modified.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-ParentId'></a>
### ParentId `property`

##### Summary

Gets or sets the parent identifier.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-ParentTitle'></a>
### ParentTitle `property`

##### Summary

Gets or sets the parent title.

<a name='P-TestCoordinator-Web-ViewModels-IViewModel`1-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='T-TestCoordinator-Web-MvcApplication'></a>
## MvcApplication `type`

##### Namespace

TestCoordinator.Web

##### Summary

Note: For instructions on enabling IIS6 or IIS7 classic mode, 
visit http://go.microsoft.com/?LinkId=9394801

<a name='M-TestCoordinator-Web-MvcApplication-Application_Start'></a>
### Application_Start() `method`

##### Summary

Application start entry point.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Models-Node'></a>
## Node `type`

##### Namespace

TestCoordinator.Web.Models

##### Summary

Represents a node in the breadcrumb

<a name='P-TestCoordinator-Web-Models-Node-ItemClass'></a>
### ItemClass `property`

##### Summary

Gets or sets the item class.

<a name='P-TestCoordinator-Web-Models-Node-ParentItemChildrenUrlFormat'></a>
### ParentItemChildrenUrlFormat `property`

##### Summary

Gets or sets the parent item children URL format.

<a name='P-TestCoordinator-Web-Models-Node-ParentItemId'></a>
### ParentItemId `property`

##### Summary

Gets or sets the parent item identifier.

<a name='P-TestCoordinator-Web-Models-Node-ParentItemTitle'></a>
### ParentItemTitle `property`

##### Summary

Gets or sets the parent item title.

<a name='M-TestCoordinator-Web-Models-Node-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Determines whether the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object'), is equal to this instance.

##### Returns

`true` if the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') is equal to this instance; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') to compare with this instance. |

<a name='M-TestCoordinator-Web-Models-Node-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

Returns a hash code for this instance.

##### Returns

A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-ViewModels-ProductViewModel'></a>
## ProductViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Product ViewModel.

<a name='P-TestCoordinator-Web-ViewModels-ProductViewModel-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='M-TestCoordinator-Web-ViewModels-ProductViewModel-CreateMappings-AutoMapper-IConfiguration-'></a>
### CreateMappings(configuration) `method`

##### Summary

Creates the mappings.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| configuration | [AutoMapper.IConfiguration](#T-AutoMapper-IConfiguration 'AutoMapper.IConfiguration') | The configuration. |

<a name='T-TestCoordinator-Web-Controllers-ProductsController'></a>
## ProductsController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for Product related requests and operations.

<a name='M-TestCoordinator-Web-Controllers-ProductsController-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [ProductsController](#T-TestCoordinator-Web-Controllers-ProductsController 'TestCoordinator.Web.Controllers.ProductsController') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Web-Controllers-ProductsController-BuildBreadcrumb-System-Nullable{System-Int32}-'></a>
### BuildBreadcrumb(parentId) `method`

##### Summary

Builds the breadcrumb.

##### Returns

The breadcrumb.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Web-Controllers-ProductsController-Create-TestCoordinator-Web-ViewModels-ProductViewModel,System-Nullable{System-Int32}-'></a>
### Create(viewModel,parentId) `method`

##### Summary

Creates the item from the specified view model.

##### Returns

Redirects to all items once Create operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [TestCoordinator.Web.ViewModels.ProductViewModel](#T-TestCoordinator-Web-ViewModels-ProductViewModel 'TestCoordinator.Web.ViewModels.ProductViewModel') | The view model. |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='T-TestCoordinator-Web-Controllers-RegressionTestingController'></a>
## RegressionTestingController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

RegressionTesting functionality

##### See Also

- [System.Web.Mvc.Controller](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.Controller 'System.Web.Mvc.Controller')

<a name='M-TestCoordinator-Web-Controllers-RegressionTestingController-Index'></a>
### Index() `method`

##### Summary

Entry point for the RegressionTesting.

##### Returns

The Index RegressionTesting view.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-RegressionTestingController-Start'></a>
### Start() `method`

##### Summary

Starts the regression testing.

##### Returns

Redirects to Statistics view.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Configurations-RouteConfig'></a>
## RouteConfig `type`

##### Namespace

TestCoordinator.Web.Configurations

##### Summary

Route configuration

<a name='M-TestCoordinator-Web-Configurations-RouteConfig-RegisterRoutes-System-Web-Routing-RouteCollection-'></a>
### RegisterRoutes(routes) `method`

##### Summary

Registers the routes.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| routes | [System.Web.Routing.RouteCollection](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Routing.RouteCollection 'System.Web.Routing.RouteCollection') | The routes. |

<a name='T-TestCoordinator-Web-Controllers-SearchController'></a>
## SearchController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for search operations.

<a name='P-TestCoordinator-Web-Controllers-SearchController-UnitOfWork'></a>
### UnitOfWork `property`

##### Summary

Gets the unit of work.

<a name='M-TestCoordinator-Web-Controllers-SearchController-ByTitle-System-String-'></a>
### ByTitle(query) `method`

##### Summary

Performs a search by title.

##### Returns

The partial view with search results.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| query | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The query. |

<a name='T-TestCoordinator-Web-ViewModels-SearchResultViewModel'></a>
## SearchResultViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for the search results.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-ChildItemsControllerName'></a>
### ChildItemsControllerName `property`

##### Summary

Gets or sets the name of the child items controller.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-ControllerName'></a>
### ControllerName `property`

##### Summary

Gets or sets the name of the controller.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-SystemType'></a>
### SystemType `property`

##### Summary

Gets or sets the type of the system.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='P-TestCoordinator-Web-ViewModels-SearchResultViewModel-Type'></a>
### Type `property`

##### Summary

Gets or sets the type.

<a name='T-TestCoordinator-Web-Resources-SortOptionsSelectItems'></a>
## SortOptionsSelectItems `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Utility class for managing sort options as select items in the view.

<a name='M-TestCoordinator-Web-Resources-SortOptionsSelectItems-GetDefault'></a>
### GetDefault() `method`

##### Summary

Gets the default list of sorting select options.

##### Returns

Collection of [SelectListItem](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.SelectListItem 'System.Web.Mvc.SelectListItem') options.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Controllers-StatisticsController'></a>
## StatisticsController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for system statistics.

<a name='M-TestCoordinator-Web-Controllers-StatisticsController-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [StatisticsController](#T-TestCoordinator-Web-Controllers-StatisticsController 'TestCoordinator.Web.Controllers.StatisticsController') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Web-Controllers-StatisticsController-AllProducts'></a>
### AllProducts() `method`

##### Summary

Retrieves all products' statistics.

##### Returns

Partial view with statistics.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-StatisticsController-General'></a>
### General() `method`

##### Summary

Retrieves the general statistics for the system.

##### Returns

Partial view with general statistics.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-StatisticsController-Index'></a>
### Index() `method`

##### Summary

Retrieves the full system statistics.

##### Returns

The Index Statistics view.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Web-Controllers-StatisticsController-Product-System-Int32-'></a>
### Product(id) `method`

##### Summary

Retrieves statistics for specific product.

##### Returns

Partial view with statistics.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The identifier. |

<a name='T-TestCoordinator-Web-ViewModels-StatisticsViewModel'></a>
## StatisticsViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

View model for the statistics.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-AreasCount'></a>
### AreasCount `property`

##### Summary

Gets or sets the areas count.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-AutomationChartData'></a>
### AutomationChartData `property`

##### Summary

Gets the automation chart data.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-FeaturesCount'></a>
### FeaturesCount `property`

##### Summary

Gets or sets the features count.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-ProductsCount'></a>
### ProductsCount `property`

##### Summary

Gets or sets the products count.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-StatusesChartData'></a>
### StatusesChartData `property`

##### Summary

Gets the statuses chart data.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-TestCases'></a>
### TestCases `property`

##### Summary

Gets or sets the test cases.

<a name='P-TestCoordinator-Web-ViewModels-StatisticsViewModel-TestCasesCount'></a>
### TestCasesCount `property`

##### Summary

Gets the test cases count.

<a name='T-TestCoordinator-Web-ViewModels-TestCaseViewModel'></a>
## TestCaseViewModel `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

TestCase ViewModel.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Attachments'></a>
### Attachments `property`

##### Summary

Gets or sets the attachments list.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Automated'></a>
### Automated `property`

##### Summary

Gets or sets a value indicating whether this [TestCase](#T-TestCoordinator-Model-TestCase 'TestCoordinator.Model.TestCase') is automated.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-AutomatedTests'></a>
### AutomatedTests `property`

##### Summary

Gets or sets the automated test cases.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Bugs'></a>
### Bugs `property`

##### Summary

Gets or sets the associated bugs.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Environment'></a>
### Environment `property`

##### Summary

Gets or sets the environment.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Given'></a>
### Given `property`

##### Summary

Gets or sets the given.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Priority'></a>
### Priority `property`

##### Summary

Gets or sets the priority.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-ProductVersion'></a>
### ProductVersion `property`

##### Summary

Gets or sets the product version.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Status'></a>
### Status `property`

##### Summary

Gets or sets the status.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-Then'></a>
### Then `property`

##### Summary

Gets or sets the then.

<a name='P-TestCoordinator-Web-ViewModels-TestCaseViewModel-When'></a>
### When `property`

##### Summary

Gets or sets the when.

<a name='M-TestCoordinator-Web-ViewModels-TestCaseViewModel-CreateMappings-AutoMapper-IConfiguration-'></a>
### CreateMappings(configuration) `method`

##### Summary

Creates the mappings.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| configuration | [AutoMapper.IConfiguration](#T-AutoMapper-IConfiguration 'AutoMapper.IConfiguration') | The configuration. |

<a name='T-TestCoordinator-Web-Controllers-TestCasesController'></a>
## TestCasesController `type`

##### Namespace

TestCoordinator.Web.Controllers

##### Summary

Responsible for Test cases related requests and operations.

<a name='M-TestCoordinator-Web-Controllers-TestCasesController-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [TestCasesController](#T-TestCoordinator-Web-Controllers-TestCasesController 'TestCoordinator.Web.Controllers.TestCasesController') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Web-Controllers-TestCasesController-BuildBreadcrumb-System-Nullable{System-Int32}-'></a>
### BuildBreadcrumb(parentId) `method`

##### Summary

Builds the breadcrumb.

##### Returns

The breadcrumb.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Web-Controllers-TestCasesController-Create-TestCoordinator-Web-ViewModels-TestCaseViewModel,System-Nullable{System-Int32}-'></a>
### Create(viewModel,parentId) `method`

##### Summary

Creates the item from the specified view model.

##### Returns

Redirects to all items once Create operation is done.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [TestCoordinator.Web.ViewModels.TestCaseViewModel](#T-TestCoordinator-Web-ViewModels-TestCaseViewModel 'TestCoordinator.Web.ViewModels.TestCaseViewModel') | The view model. |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent item identifier (if any). |

<a name='T-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions'></a>
## ViewDataDictionaryExtensions `type`

##### Namespace

TestCoordinator.Web.Custom

##### Summary

Extension methods for the ViewDataDictionary

<a name='M-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions-Add-System-Web-Mvc-ViewDataDictionary,TestCoordinator-Web-Resources-ViewDataKeys,System-Object-'></a>
### Add(viewDataDictionary,key,value) `method`

##### Summary

Adds a key-value pair to the dictionary.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewDataDictionary | [System.Web.Mvc.ViewDataDictionary](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.ViewDataDictionary 'System.Web.Mvc.ViewDataDictionary') | The view data dictionary. |
| key | [TestCoordinator.Web.Resources.ViewDataKeys](#T-TestCoordinator-Web-Resources-ViewDataKeys 'TestCoordinator.Web.Resources.ViewDataKeys') | The key as enumeration. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |

<a name='M-TestCoordinator-Web-Custom-ViewDataDictionaryExtensions-Get``1-System-Web-Mvc-ViewDataDictionary,TestCoordinator-Web-Resources-ViewDataKeys-'></a>
### Get\`\`1(viewDataDictionary,key) `method`

##### Summary

Gets a value from the dictionary using the specified key.

##### Returns

The value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewDataDictionary | [System.Web.Mvc.ViewDataDictionary](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Mvc.ViewDataDictionary 'System.Web.Mvc.ViewDataDictionary') | The view data dictionary. |
| key | [TestCoordinator.Web.Resources.ViewDataKeys](#T-TestCoordinator-Web-Resources-ViewDataKeys 'TestCoordinator.Web.Resources.ViewDataKeys') | The key as enumeration. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the value object. |

<a name='T-TestCoordinator-Web-Resources-ViewDataKeys'></a>
## ViewDataKeys `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Denotes keys used in ViewData

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-Action'></a>
### Action `constants`

##### Summary

The action

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-Breadcrumb'></a>
### Breadcrumb `constants`

##### Summary

The breadcrumb

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `constants`

##### Summary

The child items route format

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-CurrentTypeDisplayNameInPlural'></a>
### CurrentTypeDisplayNameInPlural `constants`

##### Summary

The current type display name in plural

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-CurrentTypeDisplayNameInSingular'></a>
### CurrentTypeDisplayNameInSingular `constants`

##### Summary

The current type display name in singular

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-FilterOptions'></a>
### FilterOptions `constants`

##### Summary

The filter options

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-SortOptions'></a>
### SortOptions `constants`

##### Summary

The sort options

<a name='F-TestCoordinator-Web-Resources-ViewDataKeys-Title'></a>
### Title `constants`

##### Summary

The title

<a name='T-TestCoordinator-Web-ViewModels-ViewModelBase`1'></a>
## ViewModelBase\`1 `type`

##### Namespace

TestCoordinator.Web.ViewModels

##### Summary

Base class for all ViewModel implementations.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | Generic ViewModel type. |

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ChildTypeDisplayName'></a>
### ChildTypeDisplayName `property`

##### Summary

Gets the display name of the child type.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ChildrenCount'></a>
### ChildrenCount `property`

##### Summary

Gets or sets the children count.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-DateCreated'></a>
### DateCreated `property`

##### Summary

Gets or sets the date created.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Description'></a>
### Description `property`

##### Summary

Gets or sets the description.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-LastModified'></a>
### LastModified `property`

##### Summary

Gets or sets the last modified.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ParentId'></a>
### ParentId `property`

##### Summary

Gets or sets the parent identifier.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-ParentTitle'></a>
### ParentTitle `property`

##### Summary

Gets or sets the parent title.

<a name='P-TestCoordinator-Web-ViewModels-ViewModelBase`1-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='M-TestCoordinator-Web-ViewModels-ViewModelBase`1-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Determines whether the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object'), is equal to this instance.

##### Returns

`true` if the specified [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') is equal to this instance; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The [Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') to compare with this instance. |

<a name='M-TestCoordinator-Web-ViewModels-ViewModelBase`1-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

Returns a hash code for this instance.

##### Returns

A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Web-Resources-ViewNames'></a>
## ViewNames `type`

##### Namespace

TestCoordinator.Web.Resources

##### Summary

Denotes different view names.

<a name='F-TestCoordinator-Web-Resources-ViewNames-AttachmentPartial'></a>
### AttachmentPartial `constants`

##### Summary

The attachment partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-AutomatedTestPartial'></a>
### AutomatedTestPartial `constants`

##### Summary

The automated test partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-AutomatedTestsPartial'></a>
### AutomatedTestsPartial `constants`

##### Summary

The automated tests partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-BreadcrumbPartial'></a>
### BreadcrumbPartial `constants`

##### Summary

The breadcrumb partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-BugPartial'></a>
### BugPartial `constants`

##### Summary

The bug partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-BugsPartial'></a>
### BugsPartial `constants`

##### Summary

The bugs partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-DeleteConfirmationDialogPartial'></a>
### DeleteConfirmationDialogPartial `constants`

##### Summary

The delete confirmation dialog partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-GeneralStatisticsPartial'></a>
### GeneralStatisticsPartial `constants`

##### Summary

The general statistics partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-Index'></a>
### Index `constants`

##### Summary

The Index view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-ItemDetailsFormPartial'></a>
### ItemDetailsFormPartial `constants`

##### Summary

The item details form partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-ItemLocked'></a>
### ItemLocked `constants`

##### Summary

The item locked view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-Items'></a>
### Items `constants`

##### Summary

The items view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-ItemsPartial'></a>
### ItemsPartial `constants`

##### Summary

The items partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-ManageAutomatedTestsDialogPartial'></a>
### ManageAutomatedTestsDialogPartial `constants`

##### Summary

The manage automated tests dialog partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-ManageBugsDialogPartial'></a>
### ManageBugsDialogPartial `constants`

##### Summary

The manage bugs dialog partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-NoItems'></a>
### NoItems `constants`

##### Summary

The no items view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-SearchResultsPartial'></a>
### SearchResultsPartial `constants`

##### Summary

The search results partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-StatisticsChartsPartial'></a>
### StatisticsChartsPartial `constants`

##### Summary

The statistics charts partial view name

<a name='F-TestCoordinator-Web-Resources-ViewNames-TestCasePartial'></a>
### TestCasePartial `constants`

##### Summary

The test case partial view name

<a name='T-TestCoordinator-Web-Configurations-WebApiConfig'></a>
## WebApiConfig `type`

##### Namespace

TestCoordinator.Web.Configurations

##### Summary

Web API configuration

<a name='M-TestCoordinator-Web-Configurations-WebApiConfig-Register-System-Web-Http-HttpConfiguration-'></a>
### Register(config) `method`

##### Summary

Registers the specified configuration.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| config | [System.Web.Http.HttpConfiguration](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.Http.HttpConfiguration 'System.Web.Http.HttpConfiguration') | The configuration. |
