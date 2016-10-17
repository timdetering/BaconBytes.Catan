# Settlers of Catan

## The board game called _Settlers of Catan_ brought to life with C# ##

[https://github.com/wargamer/Catan](https://github.com/wargamer/Catan)



---
Broken at:

    ---- DEBUG ASSERTION FAILED ----
    ---- Assert Short Message ----
    
    ---- Assert Long Message ----
    
    at catan.Game..ctor() in \wargamer\Catan.git\catan\Game.cs:line 64
    at catan.MainWindow..ctor() in \wargamer\Catan.git\catan\MainWindow.xaml.cs:line 25
    at System.RuntimeTypeHandle.CreateInstance(RuntimeType type, Boolean publicOnly, Boolean noCheck, Boolean& canBeCached, RuntimeMethodHandleInternal& ctor, Boolean& bNeedSecurityCheck)
    at System.RuntimeType.CreateInstanceSlow(Boolean publicOnly, Boolean skipCheckThis, Boolean fillCache, StackCrawlMark& stackMark)
    at System.RuntimeType.CreateInstanceDefaultCtor(Boolean publicOnly, Boolean skipCheckThis, Boolean fillCache, StackCrawlMark& stackMark)
    at System.Activator.CreateInstance(Type type, Boolean nonPublic)
    at System.RuntimeType.CreateInstanceImpl(BindingFlags bindingAttr, Binder binder, Object[] args, CultureInfo culture, Object[] activationAttributes, StackCrawlMark& stackMark)
    at System.Activator.CreateInstance(Type type, BindingFlags bindingAttr, Binder binder, Object[] args, CultureInfo culture, Object[] activationAttributes)
    at System.Activator.CreateInstance(Type type, Object[] args)
    at System.Xaml.Schema.SafeReflectionInvoker.CreateInstanceCritical(Type type, Object[] arguments)
    at System.Xaml.Schema.SafeReflectionInvoker.CreateInstance(Type type, Object[] arguments)
    at System.Xaml.Schema.XamlTypeInvoker.CreateInstance(Object[] arguments)
    at MS.Internal.Xaml.Runtime.ClrObjectRuntime.CreateInstanceWithCtor(XamlType xamlType, Object[] args)
    at MS.Internal.Xaml.Runtime.ClrObjectRuntime.CreateInstance(XamlType xamlType, Object[] args)
    at System.Xaml.XamlObjectWriter.Logic_CreateAndAssignToParentStart(ObjectWriterContext ctx)
    at System.Xaml.XamlObjectWriter.WriteStartMember(XamlMember property)
    at System.Xaml.XamlWriter.WriteNode(XamlReader reader)
    at System.Windows.Markup.WpfXamlLoader.TransformNodes(XamlReader xamlReader, XamlObjectWriter xamlWriter, Boolean onlyLoadOneNode, Boolean skipJournaledProperties, Boolean shouldPassLineNumberInfo, IXamlLineInfo xamlLineInfo, IXamlLineInfoConsumer xamlLineInfoConsumer, XamlContextStack`1 stack, IStyleConnector styleConnector)
    at System.Windows.Markup.WpfXamlLoader.Load(XamlReader xamlReader, IXamlObjectWriterFactory writerFactory, Boolean skipJournaledProperties, Object rootObject, XamlObjectWriterSettings settings, Uri baseUri)
    at System.Windows.Markup.WpfXamlLoader.LoadBaml(XamlReader xamlReader, Boolean skipJournaledProperties, Object rootObject, XamlAccessLevel accessLevel, Uri baseUri)
    at System.Windows.Markup.XamlReader.LoadBaml(Stream stream, ParserContext parserContext, Object parent, Boolean closeStream)
    at System.Windows.Application.LoadBamlStreamWithSyncInfo(Stream stream, ParserContext pc)
    at System.Windows.Application.LoadComponent(Uri resourceLocator, Boolean bSkipJournaledProperties)
    at System.Windows.Application.DoStartup()
    at System.Windows.Application.<.ctor>b__1_0(Object unused)
    at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
    at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
    at System.Windows.Threading.DispatcherOperation.InvokeImpl()
    at System.Windows.Threading.DispatcherOperation.InvokeInSecurityContext(Object state)
    at System.Threading.ExecutionContext.RunInternal(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
    at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
    at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state)
    at MS.Internal.CulturePreservingExecutionContext.Run(CulturePreservingExecutionContext executionContext, ContextCallback callback, Object state)
    at System.Windows.Threading.DispatcherOperation.Invoke()
    at System.Windows.Threading.Dispatcher.ProcessQueue()
    at System.Windows.Threading.Dispatcher.WndProcHook(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
    at MS.Win32.HwndWrapper.WndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam, Boolean& handled)
    at MS.Win32.HwndSubclass.DispatcherCallbackOperation(Object o)
    at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
    at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
    at System.Windows.Threading.Dispatcher.LegacyInvokeImpl(DispatcherPriority priority, TimeSpan timeout, Delegate method, Object args, Int32 numArgs)
    at MS.Win32.HwndSubclass.SubclassWndProc(IntPtr hwnd, Int32 msg, IntPtr wParam, IntPtr lParam)
    at MS.Win32.UnsafeNativeMethods.DispatchMessage(MSG& msg)
    at System.Windows.Threading.Dispatcher.PushFrameImpl(DispatcherFrame frame)
    at System.Windows.Threading.Dispatcher.PushFrame(DispatcherFrame frame)
    at System.Windows.Application.RunDispatcher(Object ignore)
    at System.Windows.Application.RunInternal(Window window)
    at System.Windows.Application.Run(Window window)
    at System.Windows.Application.Run()
    at catan.App.Main()
    at System.AppDomain._nExecuteAssembly(RuntimeAssembly assembly, String[] args)
    at System.AppDomain.ExecuteAssembly(String assemblyFile, Evidence assemblySecurity, String[] args)
    at Microsoft.VisualStudio.HostingProcess.HostProc.RunUsersAssembly()
    at System.Threading.ThreadHelper.ThreadStart_Context(Object state)
    at System.Threading.ExecutionContext.RunInternal(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
    at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state, Boolean preserveSyncCtx)
    at System.Threading.ExecutionContext.Run(ExecutionContext executionContext, ContextCallback callback, Object state)
    at System.Threading.ThreadHelper.ThreadStart()

