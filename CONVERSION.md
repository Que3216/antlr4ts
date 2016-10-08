## Conversion progress

The following files are present in the optimized Java release. As the functionality of each file is implemented and
verified by two core contributors to the TypeScript target, it will be checked off. If a file is determined to not be
necessary for the TypeScript target, it will be ~~crossed out~~ and checked off.

Prior to checking off an item here, the source file(s) where the matching functionality is implemented in TypeScript
will need a comment indicating the names of the two contributors who verified that the conversion is complete and the
semantics of the original code have been preserved. When the conversion is complete, this file and the sign-off comments
in individual files can be removed and the antlr4 submodule commit will track the progress made on this code base.

* [ ] ANTLRErrorListener.java
* [ ] ANTLRErrorStrategy.java
* [ ] ANTLRFileStream.java
* [ ] ANTLRInputStream.java
* [ ] BailErrorStrategy.java
* [ ] BaseErrorListener.java
* [ ] BufferedTokenStream.java
* [x] CharStream.java
* [ ] CommonToken.java
* [ ] CommonTokenFactory.java
* [ ] CommonTokenStream.java
* [ ] ConsoleErrorListener.java
* [ ] DefaultErrorStrategy.java
* [ ] Dependents.java
* [ ] DiagnosticErrorListener.java
* [ ] FailedPredicateException.java
* [ ] InputMismatchException.java
* [ ] InterpreterRuleContext.java
* [x] IntStream.java
* [ ] Lexer.java
* [ ] LexerInterpreter.java
* [ ] LexerNoViableAltException.java
* [ ] ListTokenSource.java
* [ ] NoViableAltException.java
* [ ] Parser.java
* [ ] ParserErrorListener.java
* [ ] ParserInterpreter.java
* [ ] ParserRuleContext.java
* [ ] ProxyErrorListener.java
* [ ] ProxyParserErrorListener.java
* [ ] RecognitionException.java
* [ ] Recognizer.java
* [ ] RuleContext.java
* [ ] RuleContextWithAltNum.java
* [ ] RuleDependencies.java
* [ ] RuleDependency.java
* [ ] RuleVersion.java
* [x] Token.java
* [x] TokenFactory.java
* [x] TokenSource.java
* [x] TokenStream.java
* [ ] TokenStreamRewriter.java
* [ ] UnbufferedCharStream.java
* [ ] UnbufferedTokenStream.java
* [x] Vocabulary.java
* [x] VocabularyImpl.java
* [x] WritableToken.java
* [x] atn\AbstractPredicateTransition.java
* [x] atn\ActionTransition.java
* [ ] atn\AmbiguityInfo.java
* [ ] atn\ArrayPredictionContext.java
* [ ] atn\ATN.java
* [ ] atn\ATNConfig.java
* [ ] atn\ATNConfigSet.java
* [x] atn\ATNDeserializationOptions.java
* [ ] atn\ATNDeserializer.java
* [ ] atn\ATNSerializer.java
* [ ] atn\ATNSimulator.java
* [x] atn\ATNState.java
  * [x] atn\ATNStateType.ts
* [x] atn\ATNType.java
* [x] atn\AtomTransition.java
* [x] atn\BasicBlockStartState.java
* [x] atn\BasicState.java
* [x] atn\BlockEndState.java
* [x] atn\BlockStartState.java
* [ ] atn\ConflictInfo.java
* [ ] atn\ContextSensitivityInfo.java
* [ ] atn\DecisionEventInfo.java
* [ ] atn\DecisionInfo.java
* [x] atn\DecisionState.java
* [ ] atn\EmptyPredictionContext.java
* [x] atn\EpsilonTransition.java
* [ ] atn\ErrorInfo.java
* [x] atn\LexerAction.java
* [ ] atn\LexerActionExecutor.java
* [x] atn\LexerActionType.java
* [ ] atn\LexerATNSimulator.java
* [ ] atn\LexerChannelAction.java
* [ ] atn\LexerCustomAction.java
* [ ] atn\LexerIndexedCustomAction.java
* [ ] atn\LexerModeAction.java
* [ ] atn\LexerMoreAction.java
* [ ] atn\LexerPopModeAction.java
* [ ] atn\LexerPushModeAction.java
* [ ] atn\LexerSkipAction.java
* [ ] atn\LexerTypeAction.java
* [ ] atn\LL1Analyzer.java
* [ ] atn\LookaheadEventInfo.java
* [x] atn\LoopEndState.java
* [x] atn\NotSetTransition.java
* [ ] atn\OrderedATNConfigSet.java
* [ ] atn\ParseInfo.java
* [ ] atn\ParserATNSimulator.java
* [x] atn\PlusBlockStartState.java
* [x] atn\PlusLoopbackState.java
* [ ] atn\PrecedencePredicateTransition.java
* [ ] atn\PredicateEvalInfo.java
* [ ] atn\PredicateTransition.java
* [ ] atn\PredictionContext.java
* [ ] atn\PredictionContextCache.java
* [ ] atn\PredictionMode.java
* [ ] atn\ProfilingATNSimulator.java
* [x] atn\RangeTransition.java
* [x] atn\RuleStartState.java
* [x] atn\RuleStopState.java
* [x] atn\RuleTransition.java
* [ ] atn\SemanticContext.java
* [x] atn\SetTransition.java
* [ ] atn\SimulatorState.java
* [ ] atn\SingletonPredictionContext.java
* [x] atn\StarBlockStartState.java
* [x] atn\StarLoopbackState.java
* [x] atn\StarLoopEntryState.java
* [x] atn\TokensStartState.java
* [x] atn\Transition.java
  * [x] atn\TransitionType.ts
  * [ ] Transition.serializationTypes?
* [x] atn\WildcardTransition.java
* [x] dfa\AbstractEdgeMap.java
* [ ] dfa\AcceptStateInfo.java
* [x] dfa\ArrayEdgeMap.java
* [ ] dfa\DFA.java
* [ ] dfa\DFASerializer.java
* [ ] dfa\DFAState.java
* [x] dfa\EdgeMap.java
* [x] dfa\EmptyEdgeMap.java
* [ ] dfa\LexerDFASerializer.java
* [x] dfa\SingletonEdgeMap.java
* [x] dfa\SparseEdgeMap.java
* [x] ~~misc\AbstractEqualityComparator.java~~ (Unnecessary in TypeScript)
* [ ] misc\Args.java
* [x] misc\Array2DHashSet.java
* [ ] misc\DoubleKeyMap.java
* [x] misc\EqualityComparator.java
* [ ] misc\FlexibleHashMap.java
* [ ] misc\Func0.java
* [ ] misc\Func1.java
* [ ] misc\IntegerList.java
* [ ] misc\IntegerStack.java
* [x] misc\Interval.java
* [x] misc\IntervalSet.java
  * [ ] IntervalSet.toIntegerList
  * [ ] IntervalSet.toSet
* [x] misc\IntSet.java
* [ ] misc\LogManager.java
* [ ] misc\MultiMap.java
* [x] misc\MurmurHash.java
* [x] misc\NotNull.java
* [x] misc\Nullable.java
* [ ] misc\NullUsageProcessor.java
* [x] misc\ObjectEqualityComparator.java
* [ ] misc\OrderedHashSet.java
* [ ] misc\ParseCancellationException.java
* [ ] misc\Predicate.java
* [ ] misc\RuleDependencyChecker.java
* [ ] misc\RuleDependencyProcessor.java
* [ ] misc\TestRig.java
* [ ] misc\Tuple.java
* [ ] misc\Tuple2.java
* [ ] misc\Tuple3.java
* [ ] misc\Utils.java
* [ ] tree\AbstractParseTreeVisitor.java
* [x] tree\ErrorNode.java
* [ ] tree\ErrorNodeImpl.java
* [x] tree\ParseTree.java
* [ ] tree\ParseTreeListener.java
* [ ] tree\ParseTreeProperty.java
* [x] tree\ParseTreeVisitor.java
* [ ] tree\ParseTreeWalker.java
* [x] tree\RuleNode.java
* [x] tree\SyntaxTree.java
* [x] tree\TerminalNode.java
* [ ] tree\TerminalNodeImpl.java
* [x] tree\Tree.java
* [ ] tree\Trees.java
* [ ] tree\pattern\Chunk.java
* [ ] tree\pattern\ParseTreeMatch.java
* [ ] tree\pattern\ParseTreePattern.java
* [ ] tree\pattern\ParseTreePatternMatcher.java
* [ ] tree\pattern\RuleTagToken.java
* [ ] tree\pattern\TagChunk.java
* [ ] tree\pattern\TextChunk.java
* [ ] tree\pattern\TokenTagToken.java
* [ ] tree\xpath\XPath.java
* [ ] tree\xpath\XPathElement.java
* [ ] tree\xpath\XPathLexer.g4
* [ ] tree\xpath\XPathLexerErrorListener.java
* [ ] tree\xpath\XPathRuleAnywhereElement.java
* [ ] tree\xpath\XPathRuleElement.java
* [ ] tree\xpath\XPathTokenAnywhereElement.java
* [ ] tree\xpath\XPathTokenElement.java
* [ ] tree\xpath\XPathWildcardAnywhereElement.java
* [ ] tree\xpath\XPathWildcardElement.java