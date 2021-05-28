//[kakao](../../index.md)/[io.github.kakaocup.kakao.recycler](index.md)



# Package io.github.kakaocup.kakao.recycler  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="io.github.kakaocup.kakao.recycler/KEmptyRecyclerItem///PointingToDeclaration/"></a>[KEmptyRecyclerItem](-k-empty-recycler-item/index.md)| <a name="io.github.kakaocup.kakao.recycler/KEmptyRecyclerItem///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [KEmptyRecyclerItem](-k-empty-recycler-item/index.md)(**parent**: Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>) : [KRecyclerItem](-k-recycler-item/index.md)<[KEmptyRecyclerItem](-k-empty-recycler-item/index.md)>   <br>More info  <br>Empty implementation of KRecyclerItemUse this if you want to perform/assert on the root view of view holder  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItem///PointingToDeclaration/"></a>[KRecyclerItem](-k-recycler-item/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItem///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open class [KRecyclerItem](-k-recycler-item/index.md)<out [T](-k-recycler-item/index.md)>(**matcher**: Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>) : [BaseActions](../io.github.kakaocup.kakao.common.actions/-base-actions/index.md), [BaseAssertions](../io.github.kakaocup.kakao.common.assertions/-base-assertions/index.md), [Interceptable](../io.github.kakaocup.kakao.intercept/-interceptable/index.md)<ViewInteraction, ViewAssertion, ViewAction>   <br>More info  <br>Base class for KRecyclerView adapter itemsPlease extend this class to provide custom recycler view item types  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItemType///PointingToDeclaration/"></a>[KRecyclerItemType](-k-recycler-item-type/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItemType///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [KRecyclerItemType](-k-recycler-item-type/index.md)<out [T](-k-recycler-item-type/index.md) : [KRecyclerItem](-k-recycler-item/index.md)<*>>(**provideItem**: (Matcher<[View](https://developer.android.com/reference/kotlin/android/view/View.html)>) -> [T](-k-recycler-item-type/index.md))  <br>More info  <br>For internal use.  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItemTypeBuilder///PointingToDeclaration/"></a>[KRecyclerItemTypeBuilder](-k-recycler-item-type-builder/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerItemTypeBuilder///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [KRecyclerItemTypeBuilder](-k-recycler-item-type-builder/index.md)  <br>More info  <br>Class that maps types to providing functionsTo be able to support different item types in KRecyclerView, this class adds support for mapping item type classes to functions that provide them.  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView///PointingToDeclaration/"></a>[KRecyclerView](-k-recycler-view/index.md)| <a name="io.github.kakaocup.kakao.recycler/KRecyclerView///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [KRecyclerView](-k-recycler-view/index.md) : [RecyclerActions](-recycler-actions/index.md), [BaseAssertions](../io.github.kakaocup.kakao.common.assertions/-base-assertions/index.md), [RecyclerAdapterAssertions](-recycler-adapter-assertions/index.md)  <br>More info  <br>View with RecyclerActions, BaseAssertions and RecyclerAdapterAssertions.  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/RecyclerActions///PointingToDeclaration/"></a>[RecyclerActions](-recycler-actions/index.md)| <a name="io.github.kakaocup.kakao.recycler/RecyclerActions///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>interface [RecyclerActions](-recycler-actions/index.md) : [ScrollableActions](../io.github.kakaocup.kakao.common.actions/-scrollable-actions/index.md), [SwipeableActions](../io.github.kakaocup.kakao.common.actions/-swipeable-actions/index.md)  <br>More info  <br>Provides ScrollableActions implementation for RecyclerView  <br><br><br>|
| <a name="io.github.kakaocup.kakao.recycler/RecyclerAdapterAssertions///PointingToDeclaration/"></a>[RecyclerAdapterAssertions](-recycler-adapter-assertions/index.md)| <a name="io.github.kakaocup.kakao.recycler/RecyclerAdapterAssertions///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>interface [RecyclerAdapterAssertions](-recycler-adapter-assertions/index.md) : [AdapterAssertions](../io.github.kakaocup.kakao.common.assertions/-adapter-assertions/index.md)  <br>More info  <br>Provides assertions for recyclerView adapter  <br><br><br>|
