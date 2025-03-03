<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [Section 5 - Block Anonymous](#section-5-block-anonymous)
   * [Block Anonymous.SQL](#block-anonymoussql)
- [Section 6 - Variables e Constant](#section-6-variables-e-constant)
   * [1 - Defining Identifiers – Variables.sql](#1-defining-identifiers-variablessql)
   * [2 - Defining Identifiers - Constantibus.sql](#2-defining-identifiers-constantibussql)
   * [3 - Types of Data no PLSQL - Datatypes.sql](#3-types-of-data-no-plsql-datatypessql)
   * [4 - Variable Bind.sql](#4-variable-bindsql)
   * [Variables e identifiers.sql](#variables-e-identifierssql)
- [Section 7 - Syntax e guidelines](#section-7-syntax-e-guidelines)
   * [1 - Syntax e Guidelines of one Block PLSQL.sql](#1-syntax-e-guidelines-of-one-block-plsqlsql)
   * [2 - Using Duties no block PLSQL.sql](#2-using-duties-no-block-plsqlsql)
   * [3 - Blocks Nestled e Scope of Identifiers.sql](#3-blocks-nestled-e-scope-of-identifierssql)
   * [4 - Standard of codification Suggested](#4-standard-of-codification-suggested)
- [Section 8 - Commands SQL no PLSQL](#section-8-commands-sql-no-plsql)
   * [1 - Using o command SELECT no PLSQL.sql](#1-using-o-command-select-no-plsqlsql)
   * [2 - Using o command INSERT no PLSQL.sql](#2-using-o-command-insert-no-plsqlsql)
   * [3 - Using o command UPDATE no PLSQL.sql](#3-using-o-command-update-no-plsqlsql)
   * [4 - Using o command DELETE no PLSQL.sql](#4-using-o-command-delete-no-plsqlsql)
   * [5 - Controlling Transactions of banco of data no PLSQL.sql](#5-controlling-transactions-of-banco-of-data-no-plsqlsql)
   * [6 - Cursor implicit.SQL](#6-cursor-implicitsql)
   * [ROWCOUNT.sql](#rowcountsql)
   * [SELECT INTO PLSQL.sql](#select-into-plsqlsql)
- [Section 9 - Structures of control](#section-9-structures-of-control)
   * [1 - Rule of precedence.sql](#1-rule-of-precedencesql)
   * [2 - IF THEN ELSIF ELSE.sql](#2-if-then-elsif-elsesql)
   * [3 - CASE.sql](#3-casesql)
   * [4 - LOOP.sql](#4-loopsql)
   * [5 - FOR LOOP.sql](#5-for-loopsql)
   * [6 - WHILE LOOP.sql](#6-while-loopsql)
   * [7 - LOOPs Anninhados.sql](#7-loops-anninhadossql)
   * [CASE.sql](#casesql)
   * [IF THEN ELSIF ELSE.sql](#if-then-elsif-elsesql)
   * [LOOPs.sql](#loopssql)
- [Section 10 - RECORD TYPE](#section-10-record-type)
   * [1 - RECORD TYPE.sql](#1-record-typesql)
   * [2 - RECORD ROWTYPE.sql](#2-record-rowtypesql)
- [Section 11 - Collections](#section-11-collections)
   * [1 - Associative arrays.sql](#1-associative-arrayssql)
   * [2 - Associative arays of RECORD.sql](#2-associative-arays-of-recordsql)
   * [3 - Nested table.sql](#3-nested-tablesql)
   * [4 - Nested table of RECORD.sql](#4-nested-table-of-recordsql)
   * [5 - VARRAY.sql](#5-varraysql)
   * [6 - VARRAY of RECORD.sql](#6-varray-of-recordsql)
   * [Associative array of RECORD.sql](#associative-array-of-recordsql)
   * [Associative array.sql](#associative-arraysql)
- [Section 12 - Cursor Explicit](#section-12-cursor-explicit)
   * [1 - Controlling cursor explicit.sql](#1-controlling-cursor-explicitsql)
   * [2 - Cursor FOR LOOP.sql](#2-cursor-for-loopsql)
   * [3 - Cursor com parameters.sql](#3-cursor-com-parameterssql)
   * [4 - SELECR FOR UPDATE.sql](#4-selecr-for-updatesql)
   * [Cursor com FOR LOOP.sql](#cursor-com-for-loopsql)
   * [Cursor com WHILE.sql](#cursor-com-whilesql)
   * [Cursor explicit.sql](#cursor-explicitsql)
- [Section 13 - EXCEPTIONS](#section-13-exceptions)
   * [1 - EXCEPTIONS.sql](#1-exceptionssql)
   * [2 - EXCEPTIONS defined.sql](#2-exceptions-definedsql)
   * [3 - PRAGMA EXCEPTION_INIT.sql](#3-pragma-exception_initsql)
- [Section 14 - Procedures](#section-14-procedures)
   * [1 - Creating one procedure.sql](#1-creating-one-proceduresql)
   * [2 - Parameters IN.sql](#2-parameters-insql)
   * [3 - Parameters IN OUT.sql](#3-parameters-in-outsql)
   * [4 - Ticket of parameters.sql](#4-ticket-of-parameterssql)
   * [5 - By collecting one procedure.sql](#5-by-collecting-one-proceduresql)
   * [6 - Removing one procedure.sql](#6-removing-one-proceduresql)
   * [Call_prc_consulta_tregado.sql](#call_prc_consulta_tregadosql)
   * [Call_prc_insere_tregado.sql](#call_prc_insere_tregadosql)
- [Section 15 - Functions](#section-15-functions)
   * [1 - Creating one function.sql](#1-creating-one-functionsql)
   * [2 - Function em command SQL.sql](#2-function-em-command-sqlsql)
   * [3 - By collecting one function.sql](#3-by-collecting-one-functionsql)
   * [4 - Removing uma function.sql](#4-removing-uma-functionsql)
   * [Call FNC_Consulta_salario_empregado.sql](#call-fnc_consulta_salario_empregadosql)
   * [Query SQL com FUNCTION.sql](#query-sql-com-functionsql)
- [Section 16 - Managing procedures e functions](#section-16-managing-procedures-e-functions)
   * [1 - Managing procedures e functions.sql](#1-managing-procedures-e-functionssql)
   * [objects-views.sql](#objects-viewssql)
- [Section 17 - Managing dependencies of objects](#section-17-managing-dependencies-of-objects)
   * [1 - Managing dependencies of objetos.sql](#1-managing-dependencies-of-objetossql)
   * [2 - DEPTREE e IDEPTREE.sql](#2-deptree-e-ideptreesql)
- [Section 18 - Packages](#section-18-packages)
   * [1 - Creating a package specification.sql](#1-creating-a-package-specificationsql)
   * [2 - Creating o package body.sql](#2-creating-o-package-bodysql)
   * [3 - Reference Components of one package.sql](#3-reference-components-of-one-packagesql)
   * [4 - Procedure of one unique execution na session & debuger.sql](#4-procedure-of-one-unique-execution-na-session-debugersql)
   * [CALL PKG e FUNCTION.sql](#call-pkg-e-functionsql)
- [Section 19 - SYS_REFCURSOR](#section-19-sys_refcursor)
   * [1 - SYS_REFCURSOR.sql](#1-sys_refcursorsql)
- [Section 20 - BULK COLLECT](#section-20-bulk-collect)
   * [1 - ASSOCIATIVE ARRAY.sql](#1-associative-arraysql)
   * [2 - NESTED TABLE.sql](#2-nested-tablesql)
   * [3 - VARRAY.sql](#3-varraysql)
- [Section 21 - FORALL e LIMIT](#section-21-forall-e-limit)
   * [1 - FORALL.sql](#1-forallsql)
   * [2 - LIMIT.sql](#2-limitsql)
- [Section 22 - SQL Dynamic](#section-22-sql-dynamic)
   * [1 - EXECUTE IMMEDIATE.sql](#1-execute-immediatesql)
   * [2 - EXECUTE IMMEDIATE with BIND VARIABLES.sql](#2-execute-immediate-with-bind-variablessql)
   * [Invoking Subprogram from Dynamic SQL Block.sql](#invoking-subprogram-from-dynamic-sql-blocksql)
- [Section 23 - DBMS_SQL](#section-23-dbms_sql)
   * [1 - DBMS_SQL.sql](#1-dbms_sqlsql)
- [Section 24 - Cursor com SQL Dynamic](#section-24-cursor-com-sql-dynamic)
   * [1 - Cursor Explicit com SQL Dynamic.sql](#1-cursor-explicit-com-sql-dynamicsql)
- [Section 25 - DBMS_SCHEDULER](#section-25-dbms_scheduler)
   * [1 - Creating one Programa.sql](#1-creating-one-programasql)
   * [2 - Creating one Agenda.sql](#2-creating-one-agendasql)
   * [3 - Creating one Job.sql](#3-creating-one-jobsql)
- [Section 26 - UTL_FILE](#section-26-utl_file)
   * [1 - UTL_FILE.sql](#1-utl_filesql)
   * [Using a Package UTL_FILE to ler e to record files.sql](#using-a-package-utl_file-to-ler-e-to-record-filessql)
- [Section 27 - DBMS_FLASHBACK](#section-27-dbms_flashback)
   * [FLASHBACK query.sql](#flashback-querysql)

<!-- TOC end -->

<!-- TOC --><a name="section-5-block-anonymous"></a>
# Section 5 - Block Anonymous


<!-- TOC --><a name="block-anonymoussql"></a>
## Block Anonymous.SQL
```sql
--
-- Seção 5 Bloco Anônimo
--
-- Aula 1 - Bloco Anônimo
-- 

-- Bloco Anônimo - Exemplo

SET SERVEROUTPUT ON
DECLARE
  vNumero1  NUMBER(11,2) := 2000;
  vNumero2  NUMBER(11,2) := 5000;
  vMedia    NUMBER(11,2);
BEGIN
  vMedia := (vnumero1 + vnumero2) / 2;
  DBMS_OUTPUT.PUT_LINE('Media = ' || vMedia);
EXCEPTION
  WHEN OTHERS 
  THEN 
    DBMS_OUTPUT.PUT_LINE('Erro Oracle: ' || SQLCODE || SQLERRM);
END;
```

<!-- TOC --><a name="section-6-variables-e-constant"></a>
# Section 6 - Variables e Constant


<!-- TOC --><a name="1-defining-identifiers-variablessql"></a>
## 1 - Defining Identifiers – Variables.sql
```sql
--
-- Seção 6 - Declaração de Identificadores - Variáveis e Constantes
--
-- Aula 1 - Definindo Identificadores – Variáveis
--
-- 

-- Declarando Variáveis 

-- Declarando uma variável Tipo NUMBER

SET SERVEROUTPUT ON
DECLARE
  vNumero    NUMBER(11,2) := 1200.50;
  
BEGIN
  DBMS_OUTPUT.PUT_LINE('Numero = ' ||   vNumero);

END;

-- Declarando variáveis Tipo CHAR e VARCHAR2

SET SERVEROUTPUT ON
DECLARE
  vCaracterTamFixo     CHAR(2) := 'RS';
  vCaracterTamVariavel VARCHAR2(100) := 'Porto Alegre, RS';
BEGIN
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Fixo = ' || vCaracterTamFixo );
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Variável = ' || vCaracterTamVariavel );
  
END;

-- Declarando variáveis Tipo DATE

SET SERVEROUTPUT ON
DECLARE
  vData1     DATE := '29/04/20';
  vData2     DATE := '29/04/2020';
BEGIN
  DBMS_OUTPUT.PUT_LINE('Data1 = ' || vData1 );
  DBMS_OUTPUT.PUT_LINE('Data2 = ' || vData2 );
END;
```

<!-- TOC --><a name="2-defining-identifiers-constantibussql"></a>
## 2 - Defining Identifiers - Constantibus.sql
```sql
--
-- Seção 6 - Declaração de Identificadores - Variáveis e Constantes
--
-- Aula 2 - Definindo Identificadores – Constantes
--
-- 

-- Declarando Constantes

-- Declarando uma Constante Tipo NUMBER

SET SERVEROUTPUT ON
DECLARE
  vPi    CONSTANT NUMBER(38,15) := 3.141592653589793;
  
BEGIN
  DBMS_OUTPUT.PUT_LINE('Pi = ' ||   vPi);

END;

-- Declarando Constante Tipo CHAR e VARCHAR2

SET SERVEROUTPUT ON
DECLARE
  vCaracterTamFixo     CONSTANT CHAR(2) := 'RS';
  vCaracterTamVariavel CONSTANT VARCHAR2(100) := 'Porto Alegre, RS';
BEGIN
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Fixo = ' || vCaracterTamFixo );
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Variável = ' || vCaracterTamVariavel );
  
END;

-- Declarando variáveis Tipo DATE

SET SERVEROUTPUT ON
DECLARE
  vData1     DATE := '29/04/20';
  vData2     DATE := '29/04/2020';
BEGIN
  DBMS_OUTPUT.PUT_LINE('Data1 = ' || vData1 );
  DBMS_OUTPUT.PUT_LINE('Data2 = ' || vData2 );
END;
```

<!-- TOC --><a name="3-types-of-data-no-plsql-datatypessql"></a>
## 3 - Types of Data no PLSQL - Datatypes.sql
```sql
--
-- Seção 6 - Declaração de Identificadores - Variáveis e Constantes
--
-- Aula 3 - Tipos de Dados no PL/SQL - Datatypes
--

-- Declarando Variáveis utilizando os principais Tipos de Dados

DECLARE
  vNumero              NUMBER(11,2) := 1200.50;
  vCaracterTamFixo     CHAR(100) := 'Texto de Tamanho Fixo de até 32767 bytes';
  vCaracterTamVariavel VARCHAR2(100) := 'Texto Tamanho variável de até 32767 bytes';
  vBooleano            BOOLEAN := TRUE;
  vData                DATE := sysdate;
  vLong                LONG := 'Texto Tamanho variável de até 32760 bytes';
  vRowid               ROWID;
  vTimestamp           TIMESTAMP := systimestamp;
  vTimestamptz         TIMESTAMP WITH TIME ZONE := systimestamp;
  vCaracterTamFixoUniversal     NCHAR(100) := 'Texto de Tamanho Fixo Universal de até 32767 bytes';
  vCaracterTamVariavelUniversal NVARCHAR2(100) := 'Texto Tamanho variável Universal de até 32767 bytes';
  vNumeroInteiro       BINARY_INTEGER := 1200;
  vNumeroFloat         BINARY_FLOAT := 15000000;
  vNumeroDouble        BINARY_DOUBLE := 15000000;
BEGIN
  DBMS_OUTPUT.PUT_LINE('Numero = ' ||   vNumero);
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Fixo = ' || vCaracterTamFixo );
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Variável = ' || vCaracterTamVariavel );
  IF  vBooleano = TRUE
  THEN 
    DBMS_OUTPUT.PUT_LINE('Booleano = ' || 'TRUE');
  ELSE
    DBMS_OUTPUT.PUT_LINE('Booleano = ' || 'FALSE OR NULL');
  END IF;
  DBMS_OUTPUT.PUT_LINE('Data = ' || vData);
  DBMS_OUTPUT.PUT_LINE('Long = ' || vLong );
  SELECT rowid
  INTO   vRowid
  FROM   employees
  WHERE  first_name = 'Steven' AND last_name = 'King';
  DBMS_OUTPUT.PUT_LINE('Rowid = ' || vRowid );
  DBMS_OUTPUT.PUT_LINE('Timestamp = ' || vTimestamp);
  DBMS_OUTPUT.PUT_LINE('Timestamp with time zone= ' || vTimestamptz);
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Fixo = ' || vCaracterTamFixoUniversal );
  DBMS_OUTPUT.PUT_LINE('String Caracteres Tam Variável = ' || vCaracterTamVariavelUniversal );
  DBMS_OUTPUT.PUT_LINE('Numero Inteiro = ' || vNumeroInteiro);
  DBMS_OUTPUT.PUT_LINE('Numero Float = ' || vNumeroFloat);
  DBMS_OUTPUT.PUT_LINE('Numero Double = ' || vNumeroDouble);
END;

```

<!-- TOC --><a name="4-variable-bindsql"></a>
## 4 - Variable Bind.sql
```sql
--
-- Seção 6 - Declaração de Identificadores - Variáveis e Constantes
--
-- Aula 4 - Variável Bind
--

-- Utilizando Variável Bind

SET SERVEROUTPUT ON
VARIABLE gmedia NUMBER
DECLARE
  vnumero1  NUMBER(11,2) := 2000;
  vnumero2  NUMBER(11,2) := 5000;
BEGIN  
  :gmedia := (vnumero1 + vnumero2) / 2;
  DBMS_OUTPUT.PUT_LINE('Media = ' || TO_CHAR(:gmedia));
EXCEPTION
  WHEN OTHERS 
  THEN 
    DBMS_OUTPUT.PUT_LINE('Erro Oracle: ' || SQLCODE || SQLERRM);
END;



```

<!-- TOC --><a name="variables-e-identifierssql"></a>
## Variables e identifiers.sql
```sql
DECLARE
  -- Quoted identifier
  "vNumero" NUMBER := 1;

  -- String
  vTexto VARCHAR2(2000) := 'Texto';

  -- Date
  vData DATE := '31/12/1997';

  -- Numeric
  vValor1 NUMBER := 1;
  vValor2 NUMBER := 1.8;
  vValor3 NUMBER := 112E10;
	
	-- Constant
	vPi CONSTANT NUMBER := 3.14;

BEGIN
  DBMS_OUTPUT.PUT_LINE("vNumero");
  DBMS_OUTPUT.PUT_LINE(vTexto);
  DBMS_OUTPUT.PUT_LINE(vData);
  DBMS_OUTPUT.PUT_LINE(vValor1);
  DBMS_OUTPUT.PUT_LINE(vValor2);
  DBMS_OUTPUT.PUT_LINE(vValor3);
	DBMS_OUTPUT.PUT_LINE(vPi);
	-- Forçando erro de constant
	-- vPi := 3.141;
	
END;

```

<!-- TOC --><a name="section-7-syntax-e-guidelines"></a>
# Section 7 - Syntax e guidelines


<!-- TOC --><a name="1-syntax-e-guidelines-of-one-block-plsqlsql"></a>
## 1 - Syntax e Guidelines of one Block PLSQL.sql
```sql
--
-- Seção 7 - Sintaxe e Diretrizes de um Bloco PL/SQL
--
-- Aula 1 - Sintaxe e Diretrizes de um Bloco PL/SQL
--

-- Comentando o Código

SET SERVEROUTPUT ON
DECLARE
  vNumero1  NUMBER(13,2);  -- Declaração de variável para o Primeiro número
  vNumero2  NUMBER(13,2);  -- Declaração de variável para o Segundo número
  vMedia    NUMBER(13,2);  -- Declaração de variável para receber a Media calculada
BEGIN
  /* Cálculo do valor da média entre dois números
     Autor: Emílio Scudero
     Data: 05/05/2020 */
	 
  vNumero1  :=  8000;
  vNumero2  :=  4000;
  vmedia    := (vNumero1 + vNumero2) / 2;           -- Cálculo da Media entre os dois números  
  DBMS_OUTPUT.PUT_LINE('vnumero1 = ' || vNumero1);  -- Impressão do Primeiro Número
  DBMS_OUTPUT.PUT_LINE('vnumero2 = ' || vNumero2);  -- Impressão do Segundo Número
  DBMS_OUTPUT.PUT_LINE('Media = ' || vMedia);     -- Impressão da Média calculada 
END;



```

<!-- TOC --><a name="2-using-duties-no-block-plsqlsql"></a>
## 2 - Using Duties no block PLSQL.sql
```sql
--
-- Seção 7 - Sintaxe e Diretrizes de um Bloco PL/SQL
--
-- Aula 2 - Utilizando Funções no bloco PL/SQL
--

--
-- Seção 7 - Sintaxe e Diretrizes de um Bloco PL/SQL
--
-- Aula 2 - Utilizando Funções no bloco PL/SQL
--

-- Utilizando Funções no bloco PL/SQL

SET SERVEROUTPUT ON
DECLARE
  vNumero1  NUMBER(13,2);  -- Declaração de variável para o Primeiro número
  vNumero2  NUMBER(13,2);  -- Declaração de variável para o Segundo número
  vMedia    NUMBER(13,2);  -- Declaração de variável para a Média
BEGIN
  /* Cálculo do valor da média entre dois números
     Autor: Emílio Scudero
     Data: 05/05/2020 */
	 
  vNumero1  :=  5000.8888;
  vNumero2  :=  3000.4444;
  vMedia    :=  ROUND((vNumero1 + vNumero2) / 2, 2);
  DBMS_OUTPUT.PUT_LINE('vnumero1 = ' || vnumero1);  -- Impressão do Primeiro Número
  DBMS_OUTPUT.PUT_LINE('vnumero2 = ' || vnumero2);  -- Impressão do Segundo Número
  DBMS_OUTPUT.PUT_LINE('Media = ' || TO_CHAR(vMedia,'99G999G999D99'));     -- Impressão da Média calculada 
END;
```

<!-- TOC --><a name="3-blocks-nestled-e-scope-of-identifierssql"></a>
## 3 - Blocks Nestled e Scope of Identifiers.sql
```sql
--
-- Seção 7 - Sintaxe e Diretrizes de um Bloco PL/SQL
--
-- Aula 3 - Blocos Aninhados e Escopo de Identificadores (variáveis e constantes)
--

-- Escopo de Identificadores e Blocos Aninhados

SET SERVEROUTPUT ON
DECLARE
  vbloco1 VARCHAR2(20) := 'Bloco 1';
BEGIN
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vbloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
  DECLARE
    vbloco2 VARCHAR2(20) := 'Bloco 2';
  BEGIN
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vbloco1);
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 2: ' || vbloco2);
  END;
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vbloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
END;

-- Identificando Blocos através de Labels

SET SERVEROUTPUT ON
<<BLOCO1>>
DECLARE
  vbloco1 VARCHAR2(20) := 'Bloco 1';
BEGIN
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || bloco1.vbloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
  <<BLOCO2>>
  DECLARE
    vbloco2 VARCHAR2(20) := 'Bloco 2';
  BEGIN
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || bloco1.vbloco1);
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 2: ' || bloco2.vbloco2);
  END;
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || bloco1.vbloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
END;
```

<!-- TOC --><a name="4-standard-of-codification-suggested"></a>
## 4 - Standard of codification Suggested
```sql
--
-- Seção 7 - Sintaxe e Diretrizes de um Bloco PL/SQL
--
-- Aula 4 - Padrões de codificação sugeridos
--

-- Exemplo de uso dos Padrões de codificação sugeridos

SET SERVEROUTPUT ON
DECLARE
  vBloco1 VARCHAR2(20) := 'Bloco 1';
BEGIN
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vBloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
  DECLARE
    vBloco2 VARCHAR2(20) := 'Bloco 2';
  BEGIN
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vBloco1);
    DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 2: ' || vBloco2);
  END;
  DBMS_OUTPUT.PUT_LINE('Referenciando variável do Bloco 1: ' || vBloco1);
  -- Se voce referencia vbloco2 aqui ocorrerá Erro
END;


```

<!-- TOC --><a name="section-8-commands-sql-no-plsql"></a>
# Section 8 - Commands SQL no PLSQL


<!-- TOC --><a name="1-using-o-command-select-no-plsqlsql"></a>
## 1 - Using o command SELECT no PLSQL.sql
```sql
--
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 2 - Utilizando o comando SELECT no PL/SQL
--

-- Utilizando o comando SELECT no PL/SQL

SET SERVEROUTPUT ON
DECLARE
   vFirst_name  employees.first_name%type;
   vLast_name   employees.last_name%type;
   vSalary      employees.salary%type;
   vEmployee_id employees.employee_id%type := 121;
BEGIN
   SELECT first_name, last_name, salary
   INTO   vfirst_name, vlast_name, vsalary
   FROM   employees
   WHERE  employee_id = vEmployee_id;
   DBMS_OUTPUT.PUT_LINE('Employee Id: ' || vEmployee_id);
   DBMS_OUTPUT.PUT_LINE('Fist Name: ' || vFirst_name);
   DBMS_OUTPUT.PUT_LINE('Last Name: ' || vLast_name);
   DBMS_OUTPUT.PUT_LINE('Salary: ' || vSalary);
END;

-- Erro ORA-01403 - No Data Found

SET SERVEROUTPUT ON
DECLARE
   vFirst_name  employees.first_name%type;
   vLast_name   employees.last_name%type;
   vSalary      employees.salary%type;
   vEmployee_id employees.employee_id%type := 50;
BEGIN
   SELECT first_name, last_name, salary
   INTO   vfirst_name, vlast_name, vsalary
   FROM   employees
   WHERE  employee_id = vEmployee_id;
   DBMS_OUTPUT.PUT_LINE('Employee Id: ' || vEmployee_id);
   DBMS_OUTPUT.PUT_LINE('Fist Name: ' || vFirst_name);
   DBMS_OUTPUT.PUT_LINE('Last Name: ' || vLast_name);
   DBMS_OUTPUT.PUT_LINE('Salary: ' || vSalary);
END;

SET SERVEROUTPUT ON
DECLARE
   vJob_id          employees.job_id%type := 'IT_PROG';
   vAvg_Salary      employees.salary%type;
   vSum_Salary      employees.salary%type;
BEGIN
   SELECT ROUND(AVG(salary),2), ROUND(SUM(salary),2)
   INTO   vAvg_Salary, vSum_Salary 
   FROM   employees
   WHERE  job_id = vJob_id;
   DBMS_OUTPUT.PUT_LINE('Cargo: ' || vJob_id);
   DBMS_OUTPUT.PUT_LINE('Média de salários: ' || vAvg_Salary);
   DBMS_OUTPUT.PUT_LINE('Somatório de salarios: ' || vSum_Salary);
END;

-- Erro ORA-01422 - Too Many Rows

SET SERVEROUTPUT ON
DECLARE
   vJob_id          employees.job_id%type;
   vAvg_Salary      employees.salary%type;
   vSum_Salary      employees.salary%type;
BEGIN
   SELECT job_id, ROUND(AVG(salary),2), ROUND(SUM(salary),2)
   INTO   vJob_id, vAvg_Salary, vSum_Salary 
   FROM   employees
   GROUP BY job_id;
   DBMS_OUTPUT.PUT_LINE('Cargo: ' || vJob_id);
   DBMS_OUTPUT.PUT_LINE('Média de salários: ' || vAvg_Salary);
   DBMS_OUTPUT.PUT_LINE('Somatório de salarios: ' || vSum_Salary);
END;
```

<!-- TOC --><a name="2-using-o-command-insert-no-plsqlsql"></a>
## 2 - Using o command INSERT no PLSQL.sql
```sql
--
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 3 - Utilizando o comando INSERT no PL/SQL
--

-- Utilizando o comando INSERT no PL/SQL

SET SERVEROUTPUT ON
DECLARE
   vfirst_name  employees.first_name%type;
   vlast_name   employees.last_name%type;
   vsalary      employees.salary%type;
BEGIN
   INSERT INTO employees 
   (employee_id, first_name, last_name, email, phone_number, hire_date,
    job_id, salary, commission_pct, manager_id, department_id)
    VALUES 
    (employees_seq.nextval, 'Kobe', 'Bryant', 'KBRYANT', '515.123.45568', SYSDATE,
     'IT_PROG', 15000, 0.4, 103, 60);
   COMMIT;  
END;


```

<!-- TOC --><a name="3-using-o-command-update-no-plsqlsql"></a>
## 3 - Using o command UPDATE no PLSQL.sql
```sql
--
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 4 - Utilizando o comando UPDATE no PL/SQL
--

-- Utilizando o comando UPDATE no PL/SQL

SET SERVEROUTPUT ON
DECLARE
   vEmployee_id    employees.employee_id%type := 150;
   vPercentual     NUMBER(3) := 10;
BEGIN
   UPDATE employees 
   SET    salary = salary * (1 + vPercentual / 100)
   WHERE  employee_id =  vEmployee_id;
   COMMIT;  
END;


```

<!-- TOC --><a name="4-using-o-command-delete-no-plsqlsql"></a>
## 4 - Using o command DELETE no PLSQL.sql
```sql
---
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 5 - Utilizando o comando DELETE no PL/SQL
--

-- Utilizando o comando DELETE no PL/SQL

-- DELETE no PL/SQL

SET SERVEROUTPUT ON
DECLARE
   vEmployee_id  employees.employee_id%type := 207;
BEGIN
   DELETE FROM employees 
   WHERE  employee_id =  vEmployee_id;
   COMMIT;  
END;

```

<!-- TOC --><a name="5-controlling-transactions-of-banco-of-data-no-plsqlsql"></a>
## 5 - Controlling Transactions of banco of data no PLSQL.sql
```sql
---
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 6 - Controlando Transações do Banco de Dados
--

-- Controlando Transações do Banco de Dados

SET SERVEROUTPUT ON
DECLARE
   vEmployee_id    employees.employee_id%type := 150;
BEGIN
   UPDATE employees 
   SET    salary = 15000
   WHERE  employee_id =  vEmployee_id;
   COMMIT;  
END;

SET SERVEROUTPUT ON
DECLARE
   vEmployee_id    employees.employee_id%type := 150;
BEGIN
   UPDATE employees 
   SET    salary = 20000
   WHERE  employee_id =  vEmployee_id;
   ROLLBACK;  
END;

BEGIN
    INSERT INTO employees 
    (employee_id, first_name, last_name, email, phone_number, hire_date,
    job_id, salary, commission_pct, manager_id, department_id)
    VALUES 
    (employees_seq.nextval, 'Kobe', 'Bryant', 'KBRYANT', '515.123.45568', SYSDATE,
    'IT_PROG', 15000, 0.4, 103, 60);
    
    SAVEPOINT INSERTOK;
    
    UPDATE employees 
    SET    salary = 30000
    WHERE  job_id = 'IT_PROG';
    
    ROLLBACK TO INSERTOK;
    COMMIT;
END;



```

<!-- TOC --><a name="6-cursor-implicitsql"></a>
## 6 - Cursor implicit.SQL
```sql
---
-- Seção 8 - Utilizando comandos SQL no PL/SQL
--
-- Aula 7 - Cursor Implícito
--

-- Utilizando atributos de Cursor Implícito

SET SERVEROUTPUT ON
DECLARE
   vdepartment_id  employees.department_id%type := 60;
   vpercentual     NUMBER(3) := 10;
BEGIN
   UPDATE employees 
   SET salary = salary * (1 + vpercentual / 100)
   WHERE department_id =  vdepartment_id;
   DBMS_OUTPUT.PUT_LINE('Numero de empregados atualizados: ' || SQL%ROWCOUNT);
   -- COMMIT;  
END;

ROLLBACK;
```

<!-- TOC --><a name="rowcountsql"></a>
## ROWCOUNT.sql
```sql
DECLARE
  vnDepartmentId employees.department_id%type := &vnDdepartmentId;
  vnPercentual   NUMBER(3) := 10;
BEGIN
  UPDATE employees e
     SET e.salary = salary * (1 + vnPercentual / 100)
   WHERE e.department_id = vnDepartmentId;

  DBMS_OUTPUT.PUT_LINE('Número de empregados atualizados: ' || SQL%ROWCOUNT);
  ROLLBACK;
END;

```

<!-- TOC --><a name="select-into-plsqlsql"></a>
## SELECT INTO PLSQL.sql
```sql
DECLARE
  vsFirstName employees.first_name%type;
  vsLastName  employees.last_name%type;
  vnSalary    employees.salary%type;
  vnId        employees.employee_id%type := &vnId;
BEGIN
  SELECT e.first_name, e.last_name, e.salary
    INTO vsFirstName, vsLastName, vnSalary
    FROM employees e
   WHERE e.employee_id = vnId;

  DBMS_OUTPUT.PUT_LINE('ID: ' || vnId);
  DBMS_OUTPUT.PUT_LINE('First name: ' || vsFirstName);
  DBMS_OUTPUT.PUT_LINE('Last name: ' || vsLastName);
  DBMS_OUTPUT.PUT_LINE('Salary: ' || vnSalary);

EXCEPTION
  WHEN NO_DATA_FOUND THEN
    RAISE_APPLICATION_ERROR(-20201, 'ID não encontrado');
  
  WHEN OTHERS THEN
    RAISE_APPLICATION_ERROR(-20202, 'Error ' || SQLERRM);
END;

```

<!-- TOC --><a name="section-9-structures-of-control"></a>
# Section 9 - Structures of control


<!-- TOC --><a name="1-rule-of-precedencesql"></a>
## 1 - Rule of precedence.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 1 - Operadores PL/SQL
--

-- Operadores PL/SQL - Com erro no cálculo devido ao mal uso da regra de precedência

SET SERVEROUTPUT ON
DECLARE
   vNota1     NUMBER(11,2) := 7.0;
   vNota2     NUMBER(11,2) := 6.0;
   vNota3     NUMBER(11,2) := 9.0;
   vNota4     NUMBER(11,2) := 6.0;
   vMedia     NUMBER(11,2);
   
BEGIN
  vMedia := (vNota1 + vNota2 + vNota3 + vNota4) / 4;
  DBMS_OUTPUT.PUT_LINE('Media = ' || vMedia);   
END;

-- Corrigindo o cálculo da média sobrepondo a regra de precedência utilizando parenteses

SET SERVEROUTPUT ON
DECLARE
   vNota1     NUMBER(11,2) := 7.0;
   vNota2     NUMBER(11,2) := 6.0;
   vNota3     NUMBER(11,2) := 9.0;
   vNota4     NUMBER(11,2) := 6.0;
   vMedia     NUMBER(11,2);
   
BEGIN
  vMedia := (vNota1 + vNota2 + vNota3 + vNota4) / 4;
  DBMS_OUTPUT.PUT_LINE('Media = ' || vMedia);   
END;


```

<!-- TOC --><a name="2-if-then-elsif-elsesql"></a>
## 2 - IF THEN ELSIF ELSE.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 2 - Utilizando o comando IF
--

-- Utilizando o comando IF

SET SERVEROUTPUT ON
ACCEPT pdepartment_id PROMPT 'Digite o Id do departamento: '
DECLARE
   vpercentual     NUMBER(3);
   vDepartment_id  employees.employee_id%type := &pdepartment_id;
BEGIN
   IF  vDepartment_id  =  80 
   THEN 
       vpercentual := 10; -- Sales
   ELSE 
       IF  vDepartment_id  =  20 
       THEN 
           vpercentual := 15; -- Marketing
       ELSE
           IF  vDepartment_id  =  60 
           THEN 
               vpercentual := 20; -- IT
           ELSE 
               vpercentual := 5;
           END IF;
       END IF;
  END IF;
  
  DBMS_OUTPUT.PUT_LINE('Id do Departamento: ' || vDepartment_id);   
  DBMS_OUTPUT.PUT_LINE('Percentual: ' || vpercentual );   
  
  UPDATE employees 
  SET    salary = salary * (1 + vpercentual / 100)
  WHERE department_id =  vDepartment_id;
  COMMIT;
END;

-- Comando IF  com ELSIF

SET SERVEROUTPUT ON
ACCEPT pdepartment_id PROMPT 'Digite o Id do departamento: '
DECLARE
   vpercentual     NUMBER(3);
   vDepartment_id  employees.employee_id%type := &pdepartment_id;
BEGIN
   IF  vDepartment_id  =  80 
   THEN 
       vpercentual := 10; -- Sales
   ELSIF vDepartment_id  =  20 
   THEN 
       vpercentual := 15; -- Marketing
   ELSIF vDepartment_id  =  60 
   THEN 
       vpercentual := 20; -- IT
   ELSE
       vpercentual := 5;
   END IF;
  
  DBMS_OUTPUT.PUT_LINE('Id do Departamento: ' || vDepartment_id);   
  DBMS_OUTPUT.PUT_LINE('percentual: ' || vpercentual );   
  
  UPDATE employees 
  SET    salary = salary * (1 + vpercentual / 100)
  WHERE department_id =  vDepartment_id;
  COMMIT;
END;
```

<!-- TOC --><a name="3-casesql"></a>
## 3 - CASE.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 3 - Utilizando o comando CASE
--

-- Utilizando o comando CASE

SET SERVEROUTPUT ON
ACCEPT pdepartment_id PROMPT 'Digite o Id do departamento: '
DECLARE
   vpercentual     NUMBER(3);
   vDepartment_id  employees.employee_id%type := &pdepartment_id;
BEGIN
   CASE  vDepartment_id 
   WHEN  80 
   THEN 
        vpercentual := 10; -- Sales
   WHEN  20 
   THEN 
         vpercentual := 15; -- Marketing
   WHEN  60 
   THEN 
         vpercentual := 20; -- IT
   ELSE 
         vpercentual := 5;
   END CASE;
   DBMS_OUTPUT.PUT_LINE('Id do Departamento: ' || vDepartment_id);   
   DBMS_OUTPUT.PUT_LINE('percentual: ' || vPercentual );   
   UPDATE employees 
   SET salary = salary * (1 + vpercentual / 100)
   WHERE department_id =  &pdepartment_id;
   COMMIT; 
 END;
 
 -- Utilizando o comando CASE
 
SET SERVEROUTPUT ON
ACCEPT pdepartment_id PROMPT 'Digite o Id do departamento: '
DECLARE
   vpercentual     NUMBER(3);
   vDepartment_id  employees.employee_id%type := &pdepartment_id;
BEGIN
   CASE  
   WHEN  vDepartment_id = 80 
   THEN 
        vpercentual := 10; -- Sales
   WHEN  vDepartment_id = 20 
   THEN 
         vpercentual := 15; -- Marketing
   WHEN  vDepartment_id = 60 
   THEN 
         vpercentual := 20; -- IT
   ELSE 
         vpercentual := 5;
   END CASE;
   DBMS_OUTPUT.PUT_LINE('Id do Departamento: ' || vDepartment_id);   
   DBMS_OUTPUT.PUT_LINE('percentual: ' || vpercentual );   
   UPDATE employees 
   SET salary = salary * (1 + vpercentual / 100)
   WHERE department_id =  &pdepartment_id;
   --COMMIT; 
 END;
```

<!-- TOC --><a name="4-loopsql"></a>
## 4 - LOOP.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 4 - LOOP Básico
--

-- LOOP Básico

SET SERVEROUTPUT ON
ACCEPT pLimite PROMPT 'Digite o valor do limite: '
DECLARE
  vNumero  NUMBER(38) := 1;
  vLimite  NUMBER(38) := &pLimite;
BEGIN
-- Imprimindo números de 1 até o limite
LOOP 
  DBMS_OUTPUT.PUT_LINE('Número = ' || to_char(vNumero));
  EXIT WHEN vNumero = vLimite;
  vNumero := vNumero + 1;
END LOOP;
END;


```

<!-- TOC --><a name="5-for-loopsql"></a>
## 5 - FOR LOOP.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 5 - FOR LOOP
--

-- FOR LOOP

SET SERVEROUTPUT ON
ACCEPT pLimite PROMPT 'Digite o valor do limite: '
DECLARE
  vInicio  INTEGER(3) := 1;
  vFim     NUMBER(38) := &pLimite;
BEGIN
FOR i IN vinicio..vfim  LOOP
  DBMS_OUTPUT.PUT_LINE('Número = ' || to_char(i) );
END LOOP;
END;

```

<!-- TOC --><a name="6-while-loopsql"></a>
## 6 - WHILE LOOP.sql
```sql
-- Seção 9 - Estruturas de Controle 
--
-- Aula 6 - WHILE LOOP
--

-- WHILE LOOP

SET SERVEROUTPUT ON
ACCEPT pLimite PROMPT 'Digite o valor do limite: '
DECLARE
  vNumero  NUMBER(38) :=  1;
  vLimite  NUMBER(38) := &pLimite;
BEGIN

-- Variaveis inicializadas na seção Declare

WHILE  vNumero <= vLimite LOOP
    DBMS_OUTPUT.PUT_LINE('Número =  ' || to_char(vNumero));
    vNumero := vNUmero + 1;
END LOOP;
END;
```

<!-- TOC --><a name="7-loops-anninhadossql"></a>
## 7 - LOOPs Anninhados.sql
```sql
--
-- Seção 9 - Estruturas de Controle 
--
-- Aula 7 - Controlando LOOPs aninhados
--

-- Controlando LOOPs aninhados

SET SERVEROUTPUT ON
DECLARE
  vTotal   NUMBER(38) :=  1;
BEGIN
<<LOOP1>>
FOR i IN 1..8 LOOP
    DBMS_OUTPUT.PUT_LINE('I =  ' || to_char(i));
    <<LOOP2>>
    FOR j IN 1..8 LOOP
      DBMS_OUTPUT.PUT_LINE('J =  ' || to_char(j));
      DBMS_OUTPUT.PUT_LINE('Total =  ' || to_char(vTotal,'99G999G999G999G999G999G999G999D99'));
      vTotal := vTotal * 2;
      -- EXIT LOOP1 WHEN vtotal > 1000000000000000;
    END LOOP;
END LOOP;
DBMS_OUTPUT.PUT_LINE('Total Final =  ' || to_char(vTotal,'99G999G999G999G999G999G999G999D99'));
END;

-- Utilizando EXIT com Label

SET SERVEROUTPUT ON
DECLARE
  vTotal   NUMBER(38) :=  1;
BEGIN
<<LOOP1>>
FOR i IN 1..8 LOOP
    DBMS_OUTPUT.PUT_LINE('I =  ' || to_char(i));
    <<LOOP2>>
    FOR j IN 1..8 LOOP
      DBMS_OUTPUT.PUT_LINE('J =  ' || to_char(j));
      DBMS_OUTPUT.PUT_LINE('Total =  ' || to_char(vTotal,'99G999G999G999G999G999G999G999D99'));
      vTotal := vTotal * 2;
      EXIT LOOP1 WHEN vtotal > 1000000000000000;
    END LOOP;
END LOOP;
DBMS_OUTPUT.PUT_LINE('Total Final =  ' || to_char(vTotal,'99G999G999G999G999G999G999G999D99'));
END;

-- Controlando LOOPs aninhados

-- Imagina um Quadrado com 10 linhas e 10 Colunas
-- Imprima todas as combinações possíveis de números de linhas e números de colunas
-- Exemplo:
--   Linha 1 - Coluna 1
--   Linha 1 - Coluna 2
--   Linha 1 - Coluna 3 
---  ...  

-- Vamos resolver em partes

-- Primeiro vamos fazer um Loop para imprimir todos os Número de Linhas

SET SERVEROUTPUT ON
DECLARE
  vContadorLinhas   NUMBER(38) :=  1;
BEGIN
<<LOOP1>>
  FOR l IN 1..10 LOOP
    DBMS_OUTPUT.PUT_LINE('Linha ' || to_char(l));	
    vContadorLinhas := vContadorLinhas + 1;
  END LOOP;
  DBMS_OUTPUT.PUT_LINE('Total de Linhas = ' || vContadorLinhas);
END;

-- Segundo vamos fazer um Loop para imprimir todos os Número de Colunas

SET SERVEROUTPUT ON
DECLARE
  vContadorColunas   NUMBER(38) :=  0;
BEGIN
<<LOOP1>>
  FOR c IN 1..10 LOOP
    DBMS_OUTPUT.PUT_LINE('Coluna ' || to_char(c));
    vContadorColunas := vContadorColunas + 1;
  END LOOP;
  DBMS_OUTPUT.PUT_LINE('Total de Colunas = ' || vContadorColunas);
END;

-- Terceiro vamos fazer um Loop para imprimir todos os Número das Linhas
--   e dentro deste Loop faremos outro Loop para imprimir os todos os Número de Colunas de cada Linha

SET SERVEROUTPUT ON
BEGIN
<<LOOP1>>
  FOR l IN 1..10 LOOP
    <<LOOP2>>
    FOR c IN 1..10 LOOP
       DBMS_OUTPUT.PUT_LINE('Linha ' || to_char(l) || ' - Coluna ' || to_char(c));    
    END LOOP;
  END LOOP;
END;

```

<!-- TOC --><a name="casesql"></a>
## CASE.sql
```sql
DECLARE
  vEntrada NUMBER;
BEGIN
  vEntrada := &pEntrada;

  CASE vEntrada
    WHEN 1 THEN
      DBMS_OUTPUT.put_line('Segunda');
    WHEN 2 THEN
      DBMS_OUTPUT.put_line('Terça');
    WHEN 3 THEN
      DBMS_OUTPUT.put_line('Quarta');
    WHEN 4 THEN
      DBMS_OUTPUT.put_line('Quinta');
    WHEN 5 THEN
      DBMS_OUTPUT.put_line('Sexta');
    WHEN 6 THEN
      DBMS_OUTPUT.put_line('Sábado');
    WHEN 7 THEN
      DBMS_OUTPUT.put_line('Domingo');
    ELSE
      DBMS_OUTPUT.put_line('Entrada inválida');
  END CASE;
END;

```

<!-- TOC --><a name="if-then-elsif-elsesql"></a>
## IF THEN ELSIF ELSE.sql
```sql
rem PL/SQL Developer Test Script

set feedback off
set autoprint off

rem Declare variables
variable vNota1 varchar2(2000)

rem Set variables
begin
  :vNota1 := null;
end;
/

rem Execute PL/SQL Block
DECLARE
  vNota1 NUMBER(11, 2) := 7.0;
  vNota2 NUMBER(11, 2) := 5.0;
  vNota3 NUMBER(11, 2) := 9.0;
  vNota4 NUMBER(11, 2) := 9.0;
  vMedia NUMBER(11, 2);
BEGIN
  -- Regra de precedência com o parenteses
  vMedia := (vNota1 + vNota2 + vNota3 + vNota4) / 4;
  DBMS_OUTPUT.PUT_LINE('Média: ' || vMedia);

  -- Estrutura IF para ver se o aluno passou de ano
  IF (vMedia >= 6) THEN
    DBMS_OUTPUT.PUT_LINE('O aluno está aprovado');
  ELSIF (vMedia >= 5) THEN
    DBMS_OUTPUT.PUT_LINE('O aluno está de recuperação');
  ELSE
    DBMS_OUTPUT.PUT_LINE('O aluno está reprovado');
  END IF;
END;
/

rem Print variables
print vNota1

```

<!-- TOC --><a name="loopssql"></a>
## LOOPs.sql
```sql
DECLARE
  vNumInicial NUMBER := 1;
  vNumFinal   NUMBER := 20;
  vNum        NUMBER;
BEGIN
  vNum := vNumInicial;
  LOOP
    DBMS_OUTPUT.put_line('Número: ' || vNum);
		
    EXIT WHEN vNum = vNumFinal; -- saia quando...
    vNum := vNum + 1;
  END LOOP;

  DBMS_OUTPUT.new_line;

  FOR i IN REVERSE 1 .. 10 LOOP
    DBMS_OUTPUT.put_line(i);
  END LOOP;

  DBMS_OUTPUT.new_line;

  vNum := 1;

  WHILE vNum <= vNumFinal LOOP
    DBMS_OUTPUT.put_line('Número: ' || vNum);
		
    EXIT WHEN vNum = vNumFinal; -- saia quando...
    vNum := vNum + 1;
  END LOOP;
END;

```

<!-- TOC --><a name="section-10-record-type"></a>
# Section 10 - RECORD TYPE


<!-- TOC --><a name="1-record-typesql"></a>
## 1 - RECORD TYPE.sql
```sql
--
-- Seção 10 - Tipos Compostos - Variável Tipo PL/SQL Record
--
-- Aula 1 - Variável Tipo PL/SQL Record
--

-- Criando um PL/SQL Record 

SET SERVEROUTPUT ON
SET VERIFY OFF
ACCEPT pemployee_id PROMPT 'Digite o Id do empregado: '
DECLARE
TYPE  employee_record_type IS RECORD 
          (employee_id   employees.employee_id%type,
           first_name    employees.first_name%type,
           last_name     employees.last_name%type,
           email         employees.email%type,
           phone_number  employees.phone_number%type);
employee_record  employee_record_type; 

BEGIN
SELECT  employee_id, first_name, last_name, email, phone_number
INTO    employee_record
FROM    employees
WHERE   employee_id = &pemployee_id;
DBMS_OUTPUT.PUT_LINE(employee_record.employee_id || ' - ' || 
                     employee_record.first_name || ' - ' || 
                     employee_record.last_name || ' - ' || 
                     employee_record.phone_number);
END;



```

<!-- TOC --><a name="2-record-rowtypesql"></a>
## 2 - RECORD ROWTYPE.sql
```sql
--
-- Seção 10 - Tipos Compostos - Variável Tipo PL/SQL Record
--
-- Aula 2 - Utilizando atributo %ROWTYPE
--

-- Criando um PL/SQL Record utilizando atributo %ROWTYPE

SET SERVEROUTPUT ON
SET VERIFY OFF
ACCEPT pemployee_id PROMPT 'Digite o Id do empregado: '
DECLARE
employee_record   employees%rowtype;
vEmployee_id      employees.employee_id%type := &pemployee_id;
BEGIN
SELECT  * 
INTO    employee_record
FROM    employees
WHERE   employee_id = vEmployee_id;
DBMS_OUTPUT.PUT_LINE(employee_record.employee_id || ' - ' || 
                     employee_record.first_name || ' - ' || 
                     employee_record.last_name || ' - ' || 
                     employee_record.phone_number || ' - ' ||
                     employee_record.job_id);
END;
```

<!-- TOC --><a name="section-11-collections"></a>
# Section 11 - Collections


<!-- TOC --><a name="1-associative-arrayssql"></a>
## 1 - Associative arrays.sql
```sql
--
-- Seção 11 - Tipos Compostos - Collections 
--
-- Aula 1 - Collections - Associative Array
--

-- Collections - Associative Array

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE Numero_Table_Type IS TABLE OF NUMBER(2) 
  INDEX BY BINARY_INTEGER;
  Numero_table  Numero_Table_Type;
BEGIN
  -- Armazena números de 1 a 10 em um Associative Array
  FOR i IN 1..10
  LOOP
    Numero_Table(i) := i;
  END LOOP;
  -- Programa faz uma série de coisas...
  -- Lê o Associative Array e imprime os números armazenados
  FOR i IN 1..10
  LOOP
    DBMS_OUTPUT.PUT_LINE('Associative Array: Indice = ' || TO_CHAR(i) || ', Valor = ' || TO_CHAR(Numero_Table(I)));
  END LOOP;
END;


```

<!-- TOC --><a name="2-associative-arays-of-recordsql"></a>
## 2 - Associative arays of RECORD.sql
```sql
--
-- Seção 11 - Tipos Compostos - Collections 
--
-- Aula 2 - Associative Array of Records - Bulk Collect
--

-- Associative Array of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS TABLE OF employees%rowtype
  INDEX BY BINARY_INTEGER;  -- Type Associative Array
  employees_table  employees_table_type;
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;

```

<!-- TOC --><a name="3-nested-tablesql"></a>
## 3 - Nested table.sql
```sql
--
-- Seção 11 - Tipos Compostos - Collections 
--
-- Aula 3 - Collections - Nested Table
--

-- Collections - Nested Table

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE Numero_Table_Type IS TABLE OF INTEGER(2);
  Numero_table numero_table_type := numero_table_type();
BEGIN
  -- Armazena números de 1 a 10 em um Nested Table
  FOR i IN 1..10
  LOOP
    Numero_Table.extend;
    Numero_Table(i) := i;
  END LOOP;
  -- O programa vai fazer muitas coisas...
  -- Lê o Nested Table e imprime os números armazenados
  FOR I IN 1..10
  LOOP
    DBMS_OUTPUT.PUT_LINE('Nested Table: Indice = ' || TO_CHAR(i) || ', Valor = ' || TO_CHAR(Numero_Table(i)));
  END LOOP;
END;



```

<!-- TOC --><a name="4-nested-table-of-recordsql"></a>
## 4 - Nested table of RECORD.sql
```sql
--
-- Seção 11 - Tipos Compostos - Collections 
--
-- Aula 4 - Nested Table of Records - Bulk Collect
--

-- Nested Table of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS TABLE OF employees%rowtype;
  employees_table  employees_table_type := employees_table_type();
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;
```

<!-- TOC --><a name="5-varraysql"></a>
## 5 - VARRAY.sql
```sql
--
-- Aula 5 - Collections - Varray
--

-- Collections - Varray

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE Numero_Table_Type IS VARRAY (10) OF INTEGER(2);
  Numero_table numero_table_type := numero_table_type();
BEGIN
  -- Armazena números de 1 a 10 em um Varray
  FOR i IN 1..10
  LOOP
    Numero_Table.extend;
    Numero_Table(i) := i;
  END LOOP;
  -- O programa vai fazer muitas coisas...
  -- Lê o Varray e imprime os números armazenados
  FOR i IN 1..10
  LOOP
    DBMS_OUTPUT.PUT_LINE('Varray: Indice = ' || TO_CHAR(i) || ', Valor = ' || TO_CHAR(Numero_Table(i)));
  END LOOP;
END;
```

<!-- TOC --><a name="6-varray-of-recordsql"></a>
## 6 - VARRAY of RECORD.sql
```sql
--
-- Seção 11 - Tipos Compostos - Collections 
--
-- Aula 6 - Varray of Records - Bulk Collect
--

-- Varray of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS VARRAY (200) OF employees%rowtype;
  employees_table  employees_table_type := employees_table_type();
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;
```

<!-- TOC --><a name="associative-array-of-recordsql"></a>
## Associative array of RECORD.sql
```sql
DECLARE
  TYPE employees_table_type IS TABLE OF employees%ROWTYPE;

  employees_table employees_table_type;
BEGIN
  SELECT * BULK COLLECT INTO employees_table FROM employees;

  FOR i IN employees_table.first .. employees_table.last LOOP
    DBMS_OUTPUT.PUT_LINE('Employee name: ' || employees_table(i).first_name || ' ' || employees_table(i).last_name);
  END LOOP;
END;


```

<!-- TOC --><a name="associative-arraysql"></a>
## Associative array.sql
```sql
DECLARE
  TYPE numero_table_type IS TABLE OF NUMBER(2) INDEX BY BINARY_INTEGER;

  numero_table numero_table_type;
BEGIN
  FOR i IN 1 .. 10 LOOP
    numero_table(i) := i;
  END LOOP;

  FOR i IN 1 .. 10 LOOP
    DBMS_OUTPUT.PUT_LINE('Associative array: Index: ' || i || ', valor: ' ||
                         numero_table(i));
  END LOOP;
END;

```

<!-- TOC --><a name="section-12-cursor-explicit"></a>
# Section 12 - Cursor Explicit


<!-- TOC --><a name="1-controlling-cursor-explicitsql"></a>
## 1 - Controlling cursor explicit.sql
```sql
--
--
-- Seção 12 - Cursor Explícito
--
-- Aula 1 - Controlando um Cursor Explícito
--

-- Controlando um Cursor Explícito com LOOP Básico

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  CURSOR  employees_cursor  IS
  SELECT  *
  FROM    employees;  -- Declaração do Cursor
  
  employees_record  employees_cursor%rowtype; 
BEGIN
  /* Inicializa */
  
  OPEN  employees_cursor;  -- Abrindo o Cursor
  
  /* Loop */
  
  LOOP  -- Loop Básico
    FETCH  employees_cursor  
    INTO  employees_record; -- Fetch do Cursor
    
    EXIT WHEN employees_cursor%notfound;
    
    DBMS_OUTPUT.PUT_LINE(employees_record.employee_id || ' - ' ||
                         employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));
    
  END LOOP;
  
  CLOSE employees_cursor; -- Close do Cursor
END;


-- Controlando um Cursor Explícito com WHILE LOOP

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  CURSOR  employees_cursor  IS
  SELECT  *
  FROM    employees; -- Declaração do Cursor
  employees_record  employees_cursor%rowtype; 
BEGIN
  /* Inicializa */
  
  OPEN  employees_cursor; -- Abrindo o Cursor
  
  FETCH  employees_cursor  
    INTO  employees_record; -- Fetch do Cursor
	
  /* Loop */
  
  WHILE  employees_cursor%found  LOOP
     DBMS_OUTPUT.PUT_LINE(employees_record.employee_id || ' - ' ||
                         employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));
    FETCH  employees_cursor  
      INTO  employees_record;
  END LOOP;
  
  CLOSE employees_cursor; -- Close do Cursor
END;

```

<!-- TOC --><a name="2-cursor-for-loopsql"></a>
## 2 - Cursor FOR LOOP.sql
```sql
--
--
-- Seção 12 - Cursor Explícito
--
-- Aula 2 - Controlando um Cursor Explícito utilizando CURSOR FOR LOOP
--

-- Controlando um Cursor Explícito utilizando CURSOR FOR LOOP

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  CURSOR  employees_cursor  IS
  SELECT  *
  FROM    employees;
BEGIN
  FOR employees_record IN  employees_cursor
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_record.employee_id || ' - ' ||
                         employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));

  END LOOP;
END;

-- CURSOR FOR LOOP utilizando Sub-consulta

SET SERVEROUTPUT ON
SET VERIFY OFF
BEGIN
  FOR employees_record IN  (SELECT  *
                            FROM    employees)
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_record.employee_id || ' - ' ||
                         employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));

  END LOOP;
END;

```

<!-- TOC --><a name="3-cursor-com-parameterssql"></a>
## 3 - Cursor com parameters.sql
```sql
--
--
-- Seção 12 - Cursor Explícito
--
-- Aula 3 - Cursor Explícito com Parâmetros
--

-- CURSOR FOR LOOP com parâmetros

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  CURSOR  employees_cursor 
         (pdepartment_id NUMBER,
          pjob_id VARCHAR2)
  IS
  SELECT  *
  FROM    employees
  WHERE   department_id = pdepartment_id  AND
          job_id = pjob_id;
BEGIN
  FOR employees_record IN  employees_cursor (60, 'IT_PROG')
  LOOP
     DBMS_OUTPUT.PUT_LINE(employees_record.employee_id || ' - ' ||
                         employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));

  END LOOP;
END;


```

<!-- TOC --><a name="4-selecr-for-updatesql"></a>
## 4 - SELECR FOR UPDATE.sql
```sql
--
--
-- Seção 12 - Cursor Explícito
--
-- Aula 4 - Cursor Explícito com SELECT FOR UPDATE
--

-- Cursor Explícito com SELECT FOR UPDATE

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  CURSOR  employees_cursor (pjob_id VARCHAR2)
  IS
  SELECT  *
  FROM    employees
  WHERE   job_id = pjob_id
  FOR UPDATE;
BEGIN
  FOR employees_record IN  employees_cursor ('AD_VP')
  LOOP
      UPDATE employees
      SET salary = salary * (1 + 10 / 100)
      WHERE CURRENT OF employees_cursor;
  END LOOP;
  COMMIT;
END;



```

<!-- TOC --><a name="cursor-com-for-loopsql"></a>
## Cursor com FOR LOOP.sql
```sql
DECLARE
  -- Declaração do Cursor
  CURSOR employees_cursor(pEmployee_id NUMBER) IS
    SELECT * FROM employees e WHERE e.employee_id = pEmployee_id;

BEGIN
  -- Loop
  FOR vEmployeesRecord IN employees_cursor(100) LOOP
  
    DBMS_OUTPUT.PUT_LINE('Employee name: ' || vEmployeesRecord.first_name || ' ' ||
                         vEmployeesRecord.last_name);
  
  END LOOP;
END;

```

<!-- TOC --><a name="cursor-com-whilesql"></a>
## Cursor com WHILE.sql
```sql
DECLARE
  -- Declaração do Cursor
  CURSOR employees_cursor IS
    SELECT * FROM EMPLOYEES;

  -- RECORD com a mesma estrutura do Cursor
  employees_record employees_cursor%ROWTYPE;
BEGIN
  -- Inicializa o Cursor
  OPEN employees_cursor;

  FETCH employees_cursor
    INTO employees_record;

  -- Loop
  WHILE employees_cursor%FOUND LOOP
  
    DBMS_OUTPUT.PUT_LINE('Employee name: ' || employees_record.first_name || ' ' ||
                         employees_record.last_name);
  
    FETCH employees_cursor
      INTO employees_record;
  END LOOP;

  -- Fechando o Cursor
  CLOSE employees_cursor;

END;

```

<!-- TOC --><a name="cursor-explicitsql"></a>
## Cursor explicit.sql
```sql
DECLARE
  -- Declaração do Cursor
  CURSOR employees_cursor IS
    SELECT * FROM EMPLOYEES;

  -- RECORD com a mesma estrutura do Cursor
  employees_record employees_cursor%ROWTYPE;
BEGIN
  -- Inicializa o Cursor
  OPEN employees_cursor;

  -- Loop
  LOOP
    FETCH employees_cursor
      INTO employees_record;
  
    EXIT WHEN employees_cursor%NOTFOUND;
  
    DBMS_OUTPUT.PUT_LINE('Employee name: ' || employees_record.first_name || ' ' ||
                         employees_record.last_name);
  
  END LOOP;

  -- Fechando o Cursor
  CLOSE employees_cursor;

END;

```

<!-- TOC --><a name="section-13-exceptions"></a>
# Section 13 - EXCEPTIONS


<!-- TOC --><a name="1-exceptionssql"></a>
## 1 - EXCEPTIONS.sql
```sql
--
--
-- Seção 13 - Tratamento de Exceções
--
-- Aula 1 - Tratamento de Exceções
--

-- Tratamento de Exceções Pré-definidas Oracle

SET SERVEROUTPUT ON
SET VERIFY OFF
ACCEPT  pEmployee_id PROMPT 'Digite o Id do Empregado: '
DECLARE
  vFirst_name   employees.first_name%TYPE;
  vLast_name    employees.last_name%TYPE;
  vEmployee_id  employees.employee_id%TYPE := &pEmployee_id;
BEGIN
  SELECT first_name, last_name
  INTO   vfirst_name, vlast_name
  FROM   employees
  WHERE  employee_id = vEmployee_id;

  DBMS_OUTPUT.PUT_LINE('Empregado: ' || vfirst_name || ' ' || vlast_name);
 
EXCEPTION
  WHEN NO_DATA_FOUND 
  THEN
     RAISE_APPLICATION_ERROR(-20001, 'Empregado não encontrado, id = ' || 
     TO_CHAR(vEmployee_id));
  WHEN OTHERS 
  THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle - ' || SQLCODE || SQLERRM);

END;



```

<!-- TOC --><a name="2-exceptions-definedsql"></a>
## 2 - EXCEPTIONS defined.sql
```sql
--
--
-- Seção 13 - Tratamento de Exceções
--
-- Aula 2 - Exceções Definidas pelo Desenvolvedor
--

-- Exceções Definidas pelo Desenvolvedor 

SET SERVEROUTPUT ON
SET VERIFY OFF
ACCEPT  pEmployee_id PROMPT 'Digite o Id do Empregado: '
DECLARE
   vFirst_name    employees.first_name%Type;
   vLast_name     employees.last_name%Type;
   vJob_id        employees.job_id%type;
   vEmployee_id   employees.employee_id%TYPE := &pEmployee_id;
   ePresident     EXCEPTION;
BEGIN
   SELECT first_name, last_name, job_id
   INTO   vFirst_name, vLast_name, vJob_id
   FROM   employees
   WHERE  employee_id = vEmployee_id;

   IF   vJob_id = 'AD_PRES' 
   THEN
        RAISE ePresident;  
   END IF;

EXCEPTION
  WHEN NO_DATA_FOUND 
  THEN
     RAISE_APPLICATION_ERROR(-20001, 'Empregado não encontrado, id = ' || 
     TO_CHAR(vEmployee_id));
  WHEN ePresident 
  THEN
       UPDATE employees
       SET    salary = salary * 1.5
       WHERE  employee_id = vEmployee_id;
       COMMIT;
  WHEN OTHERS 
  THEN
       RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;
```

<!-- TOC --><a name="3-pragma-exception_initsql"></a>
## 3 - PRAGMA EXCEPTION_INIT.sql
```sql
--
--
-- Seção 13 - Tratamento de Exceções
--
-- Aula 3 - PRAGMA EXCEPTION INIT
--

-- PRAGMA EXCEPTION INIT

DECLARE
   vemployee_id    employees.employee_id%TYPE := 300;
   vfirst_name     employees.first_name%TYPE := 'Robert';
   vlast_name      employees.last_name%TYPE := 'Ford';
   vjob_id         employees.job_id%TYPE := 'XX_YYYY';
   vphone_number   employees.phone_number%TYPE := '650.511.9844';
   vemail          employees.email%TYPE := 'RFORD';
   efk_inexistente EXCEPTION;
   PRAGMA EXCEPTION_INIT(efk_inexistente, -2291);

BEGIN
   INSERT INTO employees (employee_id, first_name, last_name, phone_number, email, hire_date,job_id)
   VALUES (vemployee_id, vfirst_name, vlast_name, vphone_number, vemail, sysdate, vjob_id);
EXCEPTION
   WHEN  efk_inexistente 
   THEN
         RAISE_APPLICATION_ERROR(-20003, 'Job inexistente!');
   WHEN OTHERS 
   THEN
         RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Forçando o Erro para descobrir o código de Erro a ser tratado

   INSERT INTO employees (employee_id, first_name, last_name, phone_number, email, hire_date, job_id)
   VALUES (employees_seq.nextval, 'Joseph', 'Smith', '3333333', 'JSMITH', sysdate, 'ZZZZ_XX');
```

<!-- TOC --><a name="section-14-procedures"></a>
# Section 14 - Procedures


<!-- TOC --><a name="1-creating-one-proceduresql"></a>
## 1 - Creating one procedure.sql
```sql
--
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 1 - Criando Procedures de Banco de Dados
--

-- Criando uma Procedure de Banco de Dados

CREATE OR REPLACE PROCEDURE PRC_INSERE_EMPREGADO
  (pfirst_name    IN VARCHAR2,
   plast_name     IN VARCHAR2,
   pemail         IN VARCHAR2,
   pphone_number  IN VARCHAR2,
   phire_date     IN DATE DEFAULT SYSDATE,
   pjob_id        IN VARCHAR2,
   pSALARY        IN NUMBER,
   pCOMMICION_PCT IN NUMBER,
   pMANAGER_ID    IN NUMBER,
   pDEPARTMENT_ID IN NUMBER)
IS 
  -- Nenhuma váriável declarada
BEGIN
  INSERT INTO employees (
    employee_id,
    first_name,
    last_name,
    email,
    phone_number,
    hire_date,
    job_id,
    salary,
    commission_pct,
    manager_id,
    department_id )
  VALUES (
    employees_seq.nextval,
    pfirst_name,
    plast_name,
    pemail,
    pphone_number,
    phire_date,
    pjob_id,
    psalary,
    pcommicion_pct,
    pmanager_id,
    pdepartment_id );
EXCEPTION
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando a Procedure pelo Bloco PL/SQL

BEGIN
  PRC_INSERE_EMPREGADO('David', 'Bowie','DBOWIE','515.127.4861',SYSDATE,'IT_PROG',15000,NULL,103,60);
  COMMIT;
END;

-- Consultando o empregado inserido
SELECT *
FROM   employees
WHERE  first_name = 'David' AND
       last_name = 'Bowie';

-- Executando a Procedure com o comando EXECUTE do SQL*PLUS

EXEC PRC_INSERE_EMPREGADO('Greg', 'Lake','GLAKE','515.127.4961',SYSDATE,'IT_PROG',15000,NULL,103,60)

COMMIT;

-- Consultando o empregado inserido
SELECT *
FROM   employees
WHERE  first_name = 'Greg' AND
       last_name = 'Lake';



```

<!-- TOC --><a name="2-parameters-insql"></a>
## 2 - Parameters IN.sql
```sql
--
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 2 - Utilizando Parametros tipo IN
--

-- Utilizando Parametros tipo IN

CREATE OR REPLACE PROCEDURE PRC_AUMENTA_SALARIO_EMPREGADO
  (pemployee_id   IN NUMBER,
   ppercentual    IN NUMBER)
IS
  -- Nenhuma váriável declarada
BEGIN
  UPDATE employees 
  SET salary = salary * (1 + ppercentual / 100)
  WHERE employee_id = pemployee_id;

EXCEPTION
  WHEN OTHERS 
  THEN
     RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle: ' || SQLCODE || ' - ' || SQLERRM);
END;

- Executando a Procedure pelo Bloco PL/SQL

BEGIN
  PRC_AUMENTA_SALARIO_EMPREGADO(109,10);
  COMMIT;
END;

```

<!-- TOC --><a name="3-parameters-in-outsql"></a>
## 3 - Parameters IN OUT.sql
```sql
--
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 3 - Utilizando Parametros tipo OUT e IN OUT
--

-- Utilizando Parametros tipo OUT 

CREATE OR REPLACE PROCEDURE PRC_CONSULTA_EMPREGADO
  (pemployee_id   IN NUMBER,
   pfirst_name    OUT VARCHAR2,
   plast_name     OUT VARCHAR2,
   pemail         OUT VARCHAR2,
   pphone_number  OUT VARCHAR2,
   phire_date     OUT DATE,
   pjob_id        OUT VARCHAR2,
   pSALARY        OUT NUMBER,
   pCOMMISSION_PCT OUT NUMBER,
   pMANAGER_ID    OUT NUMBER,
   pDEPARTMENT_ID OUT NUMBER)
IS 
  -- Nenhuma variável declarada
BEGIN
  SELECT
    first_name,
    last_name,
    email,
    phone_number,
    hire_date,
    job_id,
    salary,
    commission_pct,
    manager_id,
    department_id
  INTO 
    pfirst_name,
    plast_name,
    pemail,
    pphone_number,
    phire_date,
    pjob_id,
    psalary,
    pcommission_pct,
    pmanager_id,
    pdepartment_id
  FROM employees
  WHERE employee_id = pemployee_id;
  
EXCEPTION
  WHEN NO_DATA_FOUND THEN
     RAISE_APPLICATION_ERROR(-20001, 'Empregado Não existe: ' || pemployee_id);
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando procedure parametro Tipo OUT

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE 
  employees_record  employees%ROWTYPE;
BEGIN
  PRC_CONSULTA_EMPREGADO(100, employees_record.first_name, employees_record.last_name, employees_record.email,
    employees_record.phone_number, employees_record.hire_date, employees_record.job_id, employees_record.salary, 
    employees_record.commission_pct, employees_record.manager_id, employees_record.department_id);
    DBMS_OUTPUT.PUT_LINE(employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));
END;

-- Utilizando Parametros tipo OUT com opção NOCOPY

CREATE OR REPLACE PROCEDURE PRC_CONSULTA_EMPREGADO
  (pemployee_id   IN NUMBER,
   pfirst_name    OUT NOCOPY VARCHAR2,
   plast_name     OUT NOCOPY VARCHAR2,
   pemail         OUT NOCOPY VARCHAR2,
   pphone_number  OUT NOCOPY VARCHAR2,
   phire_date     OUT NOCOPY DATE,
   pjob_id        OUT NOCOPY VARCHAR2,
   pSALARY        OUT NOCOPY NUMBER,
   pCOMMISSION_PCT OUT NOCOPY NUMBER,
   pMANAGER_ID    OUT NOCOPY NUMBER,
   pDEPARTMENT_ID OUT NOCOPY NUMBER)
IS 
BEGIN
  SELECT
    first_name,
    last_name,
    email,
    phone_number,
    hire_date,
    job_id,
    salary,
    commission_pct,
    manager_id,
    department_id
  INTO 
    pfirst_name,
    plast_name,
    pemail,
    pphone_number,
    phire_date,
    pjob_id,
    psalary,
    pcommission_pct,
    pmanager_id,
    pdepartment_id
  FROM employees
  WHERE employee_id = pemployee_id;
  
EXCEPTION
  WHEN NO_DATA_FOUND THEN
     RAISE_APPLICATION_ERROR(-20001, 'Empregado Não existe: ' || pemployee_id);
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando procedure parametro Tipo OUT

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE 
  employees_record  employees%ROWTYPE;
BEGIN
  PRC_CONSULTA_EMPREGADO(100, employees_record.first_name, employees_record.last_name, employees_record.email,
    employees_record.phone_number, employees_record.hire_date, employees_record.job_id, employees_record.salary, 
    employees_record.commission_pct, employees_record.manager_id, employees_record.department_id);
    DBMS_OUTPUT.PUT_LINE(employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));
END;

```

<!-- TOC --><a name="4-ticket-of-parameterssql"></a>
## 4 - Ticket of parameters.sql
```sql
--
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 4 - Métodos de Passagem de Parametros
--

-- Métodos de Passagem de Parametros

-- Método Posicional

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE 
  employees_record  employees%ROWTYPE;
BEGIN
  PRC_CONSULTA_EMPREGADO(100, employees_record.first_name, employees_record.last_name, employees_record.email,
    employees_record.phone_number, employees_record.hire_date, employees_record.job_id, employees_record.salary, 
    employees_record.commission_pct, employees_record.manager_id, employees_record.department_id);
  DBMS_OUTPUT.PUT_LINE(employees_record.first_name || ' ' || 
                         employees_record.last_name || ' - ' ||
                         employees_record.department_id || ' - ' ||
                         employees_record.job_id || ' - ' ||
                         employees_record.phone_number || ' - ' ||
                         LTRIM(TO_CHAR(employees_record.salary, 'L99G999G999D99')));
END;

-- Método Nomeado

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  VEMPLOYEE_ID NUMBER := 100;
  VFIRST_NAME VARCHAR2(200);
  VLAST_NAME VARCHAR2(200);
  VEMAIL VARCHAR2(200);
  VPHONE_NUMBER VARCHAR2(200);
  VHIRE_DATE DATE;
  VJOB_ID VARCHAR2(200);
  VSALARY NUMBER;
  VCOMMISSION_PCT NUMBER;
  VMANAGER_ID NUMBER;
  VDEPARTMENT_ID NUMBER;
BEGIN

  PRC_CONSULTA_EMPREGADO(
    PEMPLOYEE_ID => VEMPLOYEE_ID,
    PFIRST_NAME => VFIRST_NAME,
    PLAST_NAME => VLAST_NAME,
    PEMAIL => VEMAIL,
    PPHONE_NUMBER => VPHONE_NUMBER,
    PHIRE_DATE => VHIRE_DATE,
    PJOB_ID => VJOB_ID,
    PSALARY => VSALARY,
    PCOMMISSION_PCT => VCOMMISSION_PCT,
    PMANAGER_ID => VMANAGER_ID,
    PDEPARTMENT_ID => VDEPARTMENT_ID
  );

  DBMS_OUTPUT.PUT_LINE('PFIRST_NAME = ' || VFIRST_NAME);
  DBMS_OUTPUT.PUT_LINE('PLAST_NAME = ' || VLAST_NAME);
  DBMS_OUTPUT.PUT_LINE('PEMAIL = ' || VEMAIL);
  DBMS_OUTPUT.PUT_LINE('PPHONE_NUMBER = ' || VPHONE_NUMBER);
  DBMS_OUTPUT.PUT_LINE('PHIRE_DATE = ' || VHIRE_DATE);
  DBMS_OUTPUT.PUT_LINE('PJOB_ID = ' || VJOB_ID);
  DBMS_OUTPUT.PUT_LINE('PSALARY = ' || VSALARY);
  DBMS_OUTPUT.PUT_LINE('PCOMMISSION_PCT = ' || VCOMMISSION_PCT);
  DBMS_OUTPUT.PUT_LINE('PMANAGER_ID = ' || VMANAGER_ID);
  DBMS_OUTPUT.PUT_LINE('PDEPARTMENT_ID = ' || VDEPARTMENT_ID);
END;


```

<!-- TOC --><a name="5-by-collecting-one-proceduresql"></a>
## 5 - By collecting one procedure.sql
```sql
--
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 5 - Recompilando Procedures de Banco de Dados
--

-- Recompilando Procedures de Banco de Dados

ALTER PROCEDURE PRC_INSERE_EMPREGADO COMPILE;






```

<!-- TOC --><a name="6-removing-one-proceduresql"></a>
## 6 - Removing one procedure.sql
```sql
---
--
-- Seção 14 - Procedures de Banco de Dados
--
-- Aula 6 - Removendo Procedure de Banco de Dados
--

-- Removendo Procedure de Banco de Dados

DROP PROCEDURE PRC_CONSULTA_EMPREGADO;

-- Recriando a Procedure para manter o exemplo do Curso

create or replace PROCEDURE PRC_CONSULTA_EMPREGADO
  (pemployee_id   IN NUMBER,
   pfirst_name    OUT NOCOPY VARCHAR2,
   plast_name     OUT NOCOPY VARCHAR2,
   pemail         OUT NOCOPY VARCHAR2,
   pphone_number  OUT NOCOPY VARCHAR2,
   phire_date     OUT NOCOPY DATE,
   pjob_id        OUT NOCOPY VARCHAR2,
   pSALARY        OUT NOCOPY NUMBER,
   pCOMMISSION_PCT OUT NOCOPY NUMBER,
   pMANAGER_ID    OUT NOCOPY NUMBER,
   pDEPARTMENT_ID OUT NOCOPY NUMBER)
IS 
BEGIN
  SELECT
    first_name,
    last_name,
    email,
    phone_number,
    hire_date,
    job_id,
    salary,
    commission_pct,
    manager_id,
    department_id
  INTO 
    pfirst_name,
    plast_name,
    pemail,
    pphone_number,
    phire_date,
    pjob_id,
    psalary,
    pcommission_pct,
    pmanager_id,
    pdepartment_id
  FROM employees
  WHERE employee_id = pemployee_id;

EXCEPTION
  WHEN NO_DATA_FOUND THEN
     RAISE_APPLICATION_ERROR(-20001, 'Empregado Não existe: ' || pemployee_id);
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;
```

<!-- TOC --><a name="call_prc_consulta_tregadosql"></a>
## Call_prc_consulta_tregado.sql
```sql
DECLARE
  employees_record employees%ROWTYPE;
BEGIN
  prc_consulta_empregado(100,
                         employees_record.first_name,
                         employees_record.last_name,
                         employees_record.email,
                         employees_record.phone_number,
                         employees_record.hire_date,
                         employees_record.job_id,
                         employees_record.salary,
                         employees_record.commission_pct,
                         employees_record.manager_id,
                         employees_record.department_id);

  dbms_output.put_line('Employee full name: ' ||
                       employees_record.first_name || ' ' ||
                       employees_record.last_name);
END;

```

<!-- TOC --><a name="call_prc_insere_tregadosql"></a>
## Call_prc_insere_tregado.sql
```sql
BEGIN
  prc_aumenta_salario_empregado(pnemployee_id => 207, pnpercentural => 30);
END;

SELECT * FROM employees a WHERE a.first_name = 'LROSA';

DECLARE
  employees_record employees%ROWTYPE;

BEGIN
  prc_consulta_empregado(pemployee_id    => 207,
                         pfirst_name     => employees_record.first_name,
                         plast_name      => employees_record.last_name,
                         pemail          => employees_record.email,
                         pphone_number   => employees_record.phone_number,
                         phire_date      => employees_record.hire_date,
                         pjob_id         => employees_record.job_id,
                         psalary         => employees_record.salary,
                         pcommission_pct => employees_record.commission_pct,
                         pmanager_id     => employees_record.manager_id,
                         pdepartment_id  => employees_record.department_id);

  dbms_output.put_line('First name: ' || employees_record.first_name);
  dbms_output.put_line('Last name: ' || employees_record.last_name);
  dbms_output.put_line('Email: ' || employees_record.email);
END;

```

<!-- TOC --><a name="section-15-functions"></a>
# Section 15 - Functions


<!-- TOC --><a name="1-creating-one-functionsql"></a>
## 1 - Creating one function.sql
```sql
--
-- Seção 15 - Funções de Banco de Dados
--
-- Aula 1 - Criando Funções de Banco de Dados
--

-- Criando Funções de Banco de Dados

CREATE OR REPLACE FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO
  (pemployee_id   IN NUMBER)
   RETURN NUMBER
IS 
  vSalary  employees.salary%TYPE;
BEGIN
  SELECT salary
  INTO   vsalary
  FROM   employees
  WHERE employee_id = pemployee_id;
  RETURN (vsalary);
EXCEPTION
  WHEN NO_DATA_FOUND THEN 
    RAISE_APPLICATION_ERROR(-20001, 'Empregado inexistente');
  WHEN OTHERS THEN
    RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || ' - ' || SQLERRM);
END;

-- Executando a Função pelo Bloco PL/SQL

SET SERVEROUTPUT ON
SET VERIFY OFF
ACCEPT pemployee_id PROMPT 'Digite o Id do empregado: '
DECLARE
  vEmployee_id  employees.employee_id%TYPE := &pemployee_id;
  vSalary       employees.salary%TYPE;
BEGIN
  vsalary := FNC_CONSULTA_SALARIO_EMPREGADO(vEmployee_id);
  DBMS_OUTPUT.PUT_LINE('Salario: ' || vsalary);
END;
```

<!-- TOC --><a name="2-function-em-command-sqlsql"></a>
## 2 - Function em command SQL.sql
```sql
--
-- Seção 15 - Funções de Banco de Dados
--
-- Aula 2 - Utilizando Funções em comandos SQL
--

-- Utilizando Funções em comandos SQL

CREATE OR REPLACE FUNCTION FNC_CONSULTA_TITULO_CARGO_EMPREGADO
  (pjob_id   IN jobs.job_id%TYPE)
   RETURN VARCHAR2
IS 
  vJob_title jobs.job_title%TYPE;
BEGIN
  SELECT job_title
  INTO   vJob_title
  FROM   jobs
  WHERE  job_id = pjob_id;
  RETURN (vJob_title);
EXCEPTION
  WHEN NO_DATA_FOUND THEN 
    RAISE_APPLICATION_ERROR(-20001, 'Job inexistente');
  WHEN OTHERS THEN
    RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || ' - ' || SQLERRM);
END;

-- Utilizando Funções em comandos SQL

SELECT employee_id, first_name, last_name, job_id, FNC_CONSULTA_TITULO_CARGO_EMPREGADO(job_id) "JOB TITLE"
FROM   employees;

-- Executando a Função pelo comando SELECT

SELECT FNC_CONSULTA_TITULO_CARGO_EMPREGADO('IT_PROG')
FROM   dual;

-- Executando a Função pelo comando SELECT

SELECT FNC_CONSULTA_SALARIO_EMPREGADO(130)
FROM   dual;
```

<!-- TOC --><a name="3-by-collecting-one-functionsql"></a>
## 3 - By collecting one function.sql
```sql
--
-- Seção 15 - Funções de Banco de Dados
--
-- Aula 3 - Recompilando Funções de Banco de Dados
--

-- Recompilando Funções de Banco de Dados

ALTER FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO COMPILE;


```

<!-- TOC --><a name="4-removing-uma-functionsql"></a>
## 4 - Removing uma function.sql
```sql
--
-- Seção 15 - Funções de Banco de Dados
--
-- Aula 4 - Removendo Funções de Banco de Dados
--

--- Removendo Funções de Banco de Dados

DROP FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO;

```

<!-- TOC --><a name="call-fnc_consulta_salario_empregadosql"></a>
## Call FNC_Consulta_salario_empregado.sql
```sql
DECLARE
  vsalary NUMBER;
BEGIN
  vsalary := fnc_consulta_salario_empregado(100);

  dbms_output.put_line('Salary: $' || vsalary);
END;

```

<!-- TOC --><a name="query-sql-com-functionsql"></a>
## Query SQL com FUNCTION.sql
```sql
SELECT e.first_name,
       e.last_name,
       e.salary,
       e.job_id,
       fnc_consulta_titulo_cargo(pjob_id => e.job_id)
  FROM employees e;

```

<!-- TOC --><a name="section-16-managing-procedures-e-functions"></a>
# Section 16 - Managing procedures e functions


<!-- TOC --><a name="1-managing-procedures-e-functionssql"></a>
## 1 - Managing procedures e functions.sql
```sql
--
-- Seção 16 - Gerenciando Procedures e Functions
--
-- Aula 1 - Gerenciando Procedures e Functions
--

-- Gerenciando Procedures e Functions

-- Consultando objetos tipo Procedure e Function do seu Usuário

DESC USER_OBJECTS

SELECT object_name, object_type, last_ddl_time, timestamp, status
FROM   user_objects
WHERE  object_type IN ('PROCEDURE', 'FUNCTION');

SELECT object_name, object_type, last_ddl_time, timestamp, status
FROM   all_objects
WHERE  object_type IN ('PROCEDURE', 'FUNCTION');

-- Consultando objetos Inválidos do schema do seu usuário 

DESC USER_OBJECTS

SELECT object_name, object_type, last_ddl_time, timestamp, status
FROM   user_objects
WHERE  status = 'INVALID';

-- Consultando o Código Fonte de Procedures e Funções  do seu usuário

DESC user_source

SELECT line, text
FROM   user_source
WHERE  name = 'PRC_INSERE_EMPREGADO' AND
       type = 'PROCEDURE'
ORDER BY line;

SELECT line, text
FROM   user_source
WHERE  name = 'FNC_CONSULTA_SALARIO_EMPREGADO' AND
       type = 'FUNCTION'
ORDER BY line;

-- Consultando a lista de parâmetros de Procedures e Funções 

DESC PRC_INSERE_EMPREGADO

DESC FNC_CONSULTA_SALARIO_EMPREGADO

-- Consultando Erros de Compilação

-- Forçando um erro de compilação

CREATE OR REPLACE FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO
  (pemployee_id   IN NUMBER)
   RETURN NUMBER
IS 
  vsalary  employees.salary%TYPE;
BEGIN
  SELECT salary
  INTO   vsalary
  FROM   employees
  WHERE employee_id = pemployee_id
  RETURN (vsalary);
EXCEPTION
  WHEN NO_DATA_FOUND THEN 
      RAISE_APPLICATION_ERROR(-20001, 'Empregado inexistente');
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Consultando Erros de Compilação - Comando SHOW ERRORS

SHOW ERRORS PROCEDURE FNC_CONSULTA_SALARIO_EMPREGADO

-- Consultando Erros de Compilação - Visão USER_ERRORS

DESC user_errors

COLUMN position FORMAT a4
COLUMN text FORMAT a60
SELECT line||'/'||position position, text
FROM   user_errors
WHERE  name = 'FNC_CONSULTA_SALARIO_EMPREGADO'
ORDER BY line;

```

<!-- TOC --><a name="objects-viewssql"></a>
## objects-views.sql
```sql
-- Consultando objetos
SELECT *
  FROM user_objects a
 WHERE a.object_type IN ('PROCEDURE', 'FUNCTION');
 
-- Consultando código fonte
SELECT *
  FROM user_source a
 WHERE a.type IN ('PROCEDURE', 'FUNCTION');
 
-- Consultando erros
SELECT *
  FROM user_errors a
 WHERE a.type IN ('PROCEDURE', 'FUNCTION');


```

<!-- TOC --><a name="section-17-managing-dependencies-of-objects"></a>
# Section 17 - Managing dependencies of objects


<!-- TOC --><a name="1-managing-dependencies-of-objetossql"></a>
## 1 - Managing dependencies of objetos.sql
```sql
--
-- Seção 17 - Gerenciando Dependências de Objetos
--
-- Aula 1 - Gerenciando Dependências de Objetos
--

-- Gerenciando Dependências de Objetos

-- Consultando Dependencias Diretas dos objetos do seu schema utilizando a visão USER_DEPENDENCIES 

DESC user_dependencies

SELECT *
FROM   user_dependencies
WHERE  referenced_name = 'EMPLOYEES' AND
       referenced_type = 'TABLE';
       
-- Consultando Dependencias Diretas e Indiretas dos objetos do seu schema utilizando a visão USER_DEPENDENCIES 

SELECT      *
FROM        user_dependencies
START WITH  referenced_name = 'EMPLOYEES' AND
            referenced_type = 'TABLE'
CONNECT BY PRIOR  name = referenced_name AND
                  type = referenced_type;
                  

-- Consultando Dependencias Diretas e Indiretas dos objetos de todos schemas utilizando a visão DBA_DEPENDENCIES        

-- Conecte-se como SYS

DESC DBA_DEPENDENCIES

SELECT      *
FROM        dba_dependencies
START WITH  referenced_owner = 'HR' AND
            referenced_name = 'EMPLOYEES' AND
            referenced_type = 'TABLE'
CONNECT BY PRIOR  owner = referenced_owner AND
                  name =  referenced_name   AND
                  type =  referenced_type;
                  
-- Consultando objetos Inválidos do schema do seu usuário 

DESC USER_OBJECTS

SELECT object_name, object_type, last_ddl_time, timestamp, status
FROM   user_objects
WHERE  status = 'INVALID';





```

<!-- TOC --><a name="2-deptree-e-ideptreesql"></a>
## 2 - DEPTREE e IDEPTREE.sql
```sql
--
-- Seção 17 - Gerenciando Dependências de Objetos
--
-- Aula 2 - Utilizando as Visões DEPTREE e IDEPTREE
--

-- Executando o script UTLDTREE

@C:\app\Emilio\product\18.0.0\dbhomeXE\rdbms\admin\utldtree.sql  

-- Obs.: Substitua o caminho de pastas pelo sua instalação

-- Executando a procedure DEPTREE_FILL

exec DEPTREE_FILL('TABLE','HR','EMPLOYEES')

-- Utilizando as Visões DEPTREE

DESC deptree

SELECT   *
FROM     deptree
ORDER by seq#


-- Utilizando as Visões IDEPTREE

desc ideptree

SELECT *
FROM ideptree;

```

<!-- TOC --><a name="section-18-packages"></a>
# Section 18 - Packages


<!-- TOC --><a name="1-creating-a-package-specificationsql"></a>
## 1 - Creating a package specification.sql
```sql
--
-- Seção 19 - Criando Packages de Banco de Dados
--
-- Aula 2 - Criando o Package Specification 
--

-- Criando o Package Specification 

create or replace PACKAGE PCK_EMPREGADOS
IS

	gMinSalary     employees.salary%TYPE;

	PROCEDURE PRC_INSERE_EMPREGADO
	(pfirst_name    IN VARCHAR2,
	plast_name     IN VARCHAR2,
	pemail         IN VARCHAR2,
	pphone_number  IN VARCHAR2,
	phire_date     IN DATE DEFAULT SYSDATE,
	pjob_id        IN VARCHAR2,
	pSALARY        IN NUMBER,
	pCOMMICION_PCT IN NUMBER,
	pMANAGER_ID    IN NUMBER,
	pDEPARTMENT_ID IN NUMBER);

	PROCEDURE PRC_AUMENTA_SALARIO_EMPREGADO
	(pemployee_id   IN NUMBER,
	ppercentual    IN NUMBER);

	FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO
	(pemployee_id   IN NUMBER)
	RETURN NUMBER;

END PCK_EMPREGADOS;


```

<!-- TOC --><a name="2-creating-o-package-bodysql"></a>
## 2 - Creating o package body.sql
```sql
--
-- Seção 19 - Criando Packages de Banco de Dados
--
-- Aula 3 - Criando o Package Body
--

-- Criando o Package Body

create or replace PACKAGE BODY PCK_EMPREGADOS
IS
	PROCEDURE PRC_INSERE_EMPREGADO
	  (pfirst_name    IN VARCHAR2,
	   plast_name     IN VARCHAR2,
	   pemail         IN VARCHAR2,
	   pphone_number  IN VARCHAR2,
	   phire_date     IN DATE DEFAULT SYSDATE,
	   pjob_id        IN VARCHAR2,
	   pSALARY        IN NUMBER,
	   pCOMMICION_PCT IN NUMBER,
	   pMANAGER_ID    IN NUMBER,
	   pDEPARTMENT_ID IN NUMBER)
	IS 
	BEGIN
	  INSERT INTO employees (
		employee_id,
		first_name,
		last_name,
		email,
		phone_number,
		hire_date,
		job_id,
		salary,
		commission_pct,
		manager_id,
		department_id )
	  VALUES (
		employees_seq.nextval,
		pfirst_name,
		plast_name,
		pemail,
		pphone_number,
		phire_date,
		pjob_id,
		psalary,
		pcommicion_pct,
		pmanager_id,
		pdepartment_id );
	EXCEPTION
	  WHEN OTHERS THEN
		 RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle ' || SQLCODE || SQLERRM);
	END;

	PROCEDURE PRC_AUMENTA_SALARIO_EMPREGADO
	  (pemployee_id   IN NUMBER,
	   ppercentual    IN NUMBER)
	IS
	  -- Nenhuma váriável declarada
	BEGIN
	  UPDATE employees 
	  SET salary = salary * (1 + ppercentual / 100)
	  WHERE employee_id = pemployee_id;

	EXCEPTION
	  WHEN OTHERS 
	  THEN
		 RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle: ' || SQLCODE || ' - ' || SQLERRM);
	END;

	FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO
	  (pemployee_id   IN NUMBER)
	   RETURN NUMBER
	IS 
	  vsalary  employees.salary%TYPE;
	BEGIN
	  SELECT salary
	  INTO   vsalary
	  FROM   employees
	  WHERE employee_id = pemployee_id;
	  RETURN (vsalary);
	EXCEPTION
	  WHEN NO_DATA_FOUND THEN 
		  RAISE_APPLICATION_ERROR(-20001, 'Empregado inexistente');
	  WHEN OTHERS THEN
		 RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
	END;

END PCK_EMPREGADOS;
```

<!-- TOC --><a name="3-reference-components-of-one-packagesql"></a>
## 3 - Reference Components of one package.sql
```sql
--
-- Seção 19 - Criando Packages de Banco de Dados
--
-- Aula 4 - Referenciando Componentes de uma Package 
--

-- Referenciando Componentes de uma Package 

BEGIN
  PCK_EMPREGADOS.PRC_INSERE_EMPREGADO('Bob', 'Dylan','BDYLAN','515.258.4861',SYSDATE,'IT_PROG',20000,NULL,103,60);
  COMMIT;
END;

BEGIN
  PCK_EMPREGADOS.PRC_INSERE_EMPREGADO('John', 'Lenon','JLENON','515.244.4861',SYSDATE,'IT_PROG',15000,NULL,103,60);
  COMMIT;
END;
```

<!-- TOC --><a name="4-procedure-of-one-unique-execution-na-session-debugersql"></a>
## 4 - Procedure of one unique execution na session & debuger.sql
```sql
--
-- Seção 19 - Criando Packages de Banco de Dados
--
-- Aula 5 - Procedimento de uma unica execução na Seção
--

-- Criando o Package Body

-- Procedimento de uma unica execução na Seção

create or replace PACKAGE BODY PCK_EMPREGADOS
IS
PROCEDURE PRC_INSERE_EMPREGADO
  (pfirst_name    IN VARCHAR2,
   plast_name     IN VARCHAR2,
   pemail         IN VARCHAR2,
   pphone_number  IN VARCHAR2,
   phire_date     IN DATE DEFAULT SYSDATE,
   pjob_id        IN VARCHAR2,
   pSALARY        IN NUMBER,
   pCOMMICION_PCT IN NUMBER,
   pMANAGER_ID    IN NUMBER,
   pDEPARTMENT_ID IN NUMBER)
IS 
BEGIN
  IF  pSalary < PCK_EMPREGADOS.gMinSalary  
  THEN
      RAISE_APPLICATION_ERROR(-20002, 'Salario não pode ser inferior ao menor salario dos empregados!');
  END IF;
      
  INSERT INTO employees (
    employee_id,
    first_name,
    last_name,
    email,
    phone_number,
    hire_date,
    job_id,
    salary,
    commission_pct,
    manager_id,
    department_id )
  VALUES (
    employees_seq.nextval,
    pfirst_name,
    plast_name,
    pemail,
    pphone_number,
    phire_date,
    pjob_id,
    psalary,
    pcommicion_pct,
    pmanager_id,
    pdepartment_id );
EXCEPTION
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

PROCEDURE PRC_AUMENTA_SALARIO_EMPREGADO
  (pemployee_id   IN NUMBER,
   ppercentual    IN NUMBER)
IS
  -- Nenhuma váriável declarada
BEGIN
  UPDATE employees 
  SET salary = salary * (1 + ppercentual / 100)
  WHERE employee_id = pemployee_id;

EXCEPTION
  WHEN OTHERS 
  THEN
     RAISE_APPLICATION_ERROR(-20001, 'Erro Oracle: ' || SQLCODE || ' - ' || SQLERRM);
END;

FUNCTION FNC_CONSULTA_SALARIO_EMPREGADO
  (pemployee_id   IN NUMBER)
   RETURN NUMBER
IS 
  vsalary  employees.salary%TYPE;
BEGIN
  SELECT salary
  INTO   vsalary
  FROM   employees
  WHERE employee_id = pemployee_id;
  RETURN (vsalary);
EXCEPTION
  WHEN NO_DATA_FOUND THEN 
      RAISE_APPLICATION_ERROR(-20001, 'Empregado inexistente');
  WHEN OTHERS THEN
     RAISE_APPLICATION_ERROR(-20002, 'Erro Oracle ' || SQLCODE || SQLERRM);
END;

BEGIN 
  SELECT MIN(salary)
  INTO   PCK_EMPREGADOS.gMinSalary
  FROM   employees;
END PCK_EMPREGADOS;
```

<!-- TOC --><a name="call-pkg-e-functionsql"></a>
## CALL PKG e FUNCTION.sql
```sql
DECLARE
  vnSalary NUMBER;
BEGIN
  SELECT PKG_EMPLOYEES.FNC_CONSULTA_SALARIO_EMPREGADO(100)
    INTO vnSalary
    FROM DUAL;

  DBMS_OUTPUT.PUT_LINE('The salary of employees with ID 100 is R$ ' ||
                       vnSalary);
END;

```

<!-- TOC --><a name="section-19-sys_refcursor"></a>
# Section 19 - SYS_REFCURSOR


<!-- TOC --><a name="1-sys_refcursorsql"></a>
## 1 - SYS_REFCURSOR.sql
```sql
--
-- Seção 23 - PL/SQL Avançado - Utilizando SYS_REFCURSOR
--
-- Aula 1 - Utilizando SYS_REFCURSOR
--

-- Utilizando SYS_REFCURSOR

CREATE OR REPLACE PROCEDURE PRC_CURSOR_EMPLOYEES
  (pemployees_cursor OUT SYS_REFCURSOR)
IS
BEGIN
  OPEN pemployees_cursor 
  FOR
	SELECT first_name, last_name 
	FROM employees;
	
END PRC_CURSOR_EMPLOYEES;

-- Procedure referenciando o Parametro OUT SYS_REFCURSOR

CREATE OR REPLACE PROCEDURE PRC_DISPLAY_EMPOYEES
IS
  employees_cursor  SYS_REFCURSOR;
  vfirst_name  employees.first_name%TYPE;
  vlast_name   employees.last_name%TYPE;
BEGIN
  PRC_CURSOR_EMPLOYEES(employees_cursor);
  
  LOOP
    FETCH  employees_cursor
    INTO   vfirst_name, vlast_name;
    EXIT   WHEN employees_cursor%NOTFOUND;
	
    DBMS_OUTPUT.PUT_LINE(vfirst_name || ' ' || vlast_name);

  END LOOP;
  
  CLOSE employees_cursor;
  
END PRC_DISPLAY_EMPOYEES;

-- Executando a Procedure PRC_DISPLAY_EMPOYEES

SET SERVEROUTPUT ON
SET VERIFY OFF
execute PRC_DISPLAY_EMPOYEES

-- Variável Cursor e Reference Cursor 

CREATE OR REPLACE FUNCTION FNC_GET_EMPOYEES
  (pemployee_id  IN NUMBER)
  RETURN SYS_REFCURSOR
IS
  employees_cursor  SYS_REFCURSOR;
BEGIN
  OPEN employees_cursor  
  FOR
    SELECT first_name, last_name
    FROM   employees
    WHERE  employee_id = pemployee_id;
    
  RETURN employees_cursor;
  
END FNC_GET_EMPOYEES;

-- Referenciando a Função

CREATE OR REPLACE PROCEDURE PRC_DISPLAY_EMPOYEES2
  (pemployee_id IN NUMBER)
IS
  employees_cursor  SYS_REFCURSOR;
  vfirst_name  employees.first_name%TYPE;
  vlast_name   employees.last_name%TYPE;
BEGIN
  employees_cursor := FNC_GET_EMPOYEES(pemployee_id);
  
  LOOP
    FETCH  employees_cursor
    INTO   vfirst_name, vlast_name;
    EXIT WHEN employees_cursor%NOTFOUND;
	
    DBMS_OUTPUT.PUT_LINE(vfirst_name || ' ' || vlast_name);

  END LOOP;
  
  CLOSE employees_cursor;
END PRC_DISPLAY_EMPOYEES2;

-- Executando a procedure 

SET SERVEROUTPUT ON
SET VERIFY OFF
execute PRC_DISPLAY_EMPOYEES2(100)


```

<!-- TOC --><a name="section-20-bulk-collect"></a>
# Section 20 - BULK COLLECT


<!-- TOC --><a name="1-associative-arraysql"></a>
## 1 - ASSOCIATIVE ARRAY.sql
```sql
--
-- Seção 24 - PL/SQL Avançado - Bulk Collect
--
-- Aula 2 - Associative Array of Records - Bulk Collect
--

-- Associative Array of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS TABLE OF employees%rowtype
  INDEX BY BINARY_INTEGER;  -- Type Associative Array
  employees_table  employees_table_type;
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;

```

<!-- TOC --><a name="2-nested-tablesql"></a>
## 2 - NESTED TABLE.sql
```sql
--
-- Seção 24 - PL/SQL Avançado - Bulk Collect
--
-- Aula 3 - Nested Table of Records - Bulk Collect
--

-- Nested Table of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS TABLE OF employees%rowtype;
  employees_table  employees_table_type := employees_table_type();
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;
```

<!-- TOC --><a name="3-varraysql"></a>
## 3 - VARRAY.sql
```sql
--
-- Seção 24 - PL/SQL Avançado - Bulk Collect
--
-- Aula 4 - Varray of Records - Bulk Collect
--

-- Varray of Records - Bulk Collect

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  TYPE employees_table_type IS VARRAY (200) OF employees%rowtype;
  employees_table  employees_table_type := employees_table_type();
BEGIN
  SELECT *
    BULK COLLECT INTO employees_table 
  FROM employees;
  FOR i IN employees_table.first..employees_table.last  
  LOOP
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' || 
                         employees_table(i).first_name || ' - ' || 
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).phone_number || ' - ' ||
                         employees_table(i).job_id || ' - ' ||
                         TO_CHAR(employees_table(i).salary,'99G999G999D99'));   
  END LOOP;
END;
```

<!-- TOC --><a name="section-21-forall-e-limit"></a>
# Section 21 - FORALL e LIMIT


<!-- TOC --><a name="1-forallsql"></a>
## 1 - FORALL.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 25 - Bulk Collect e FOR ALL
--
-- Aula 1 - Bulk Collect - FOR ALL

-- Bulk Collect 

SELECT count(*)
FROM   employees;

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_UPDATE_SALARY
  (ppercentual IN NUMBER)
AS
  TYPE employee_id_table_type IS TABLE OF employees.employee_id%TYPE 
  INDEX BY BINARY_INTEGER;  -- Type Associative Array
  employee_id_table  employee_id_table_type;
BEGIN
  SELECT DISTINCT employee_id 
    BULK COLLECT INTO employee_id_table  
  FROM employees;
  
  DBMS_OUTPUT.PUT_LINE('Linhas recuperadas: ' || employee_id_table.COUNT);
  
  FOR indice IN 1..employee_id_table.COUNT  LOOP 
    UPDATE employees e
    SET    e.salary = e.salary * (1 + ppercentual / 100)
    WHERE  e.employee_id = employee_id_table(indice);   -- para cada UPDATE dentro do FOR LOOP Ocorrerá troca de contexto (Context Switch) 
	--
    -- outro comandos
    --
  END LOOP;
	
END;

-- Consultando antes

SELECT *
FROM employees;

--- Executando PRC_UPDATE_TAX 

exec PRC_UPDATE_SALARY(10)

-- Consultando depois

SELECT *
FROM employees;

ROLLBACK;

-- Bulk Collect - FOR ALL

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_UPDATE_SALARY
  (ppercentual IN NUMBER)
AS
  TYPE employee_id_table_type IS TABLE OF employees.employee_id%TYPE 
  INDEX BY BINARY_INTEGER;  -- Type Associative Array
  employee_id_table  employee_id_table_type;
BEGIN

  SELECT DISTINCT employee_id 
    BULK COLLECT INTO employee_id_table  
  FROM employees;
  
  DBMS_OUTPUT.PUT_LINE('Linhas recuperadas: ' || employee_id_table.COUNT);
  
  FORALL indice IN 1..employee_id_table.COUNT  -- FOR ALL empacota todos os UPDATES e envia o pacote em 1 única troca de contexto (Context Switch)
    UPDATE employees e
    SET    e.salary = e.salary * (1 + ppercentual / 100)
    WHERE  e.employee_id = employee_id_table(indice); 
	
END;

-- Consultando

SELECT *
FROM employees;

--- Executando PRC_UPDATE_TAX 

exec PRC_UPDATE_SALARY(10)

-- Consultando

SELECT *
FROM employees;

ROLLBACK;
```

<!-- TOC --><a name="2-limitsql"></a>
## 2 - LIMIT.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 25 - Bulk Collect e FOR ALL
--
-- Aula 2 - Bulk Collect - FOR ALL e LIMIT

-- Bulk Collect - FOR ALL

SELECT COUNT(*)
FROM employees;

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_UPDATE_SALARY2
  (ppercentual IN NUMBER)
AS
  vLimit CONSTANT INTEGER(2) := 30;
  TYPE employee_id_table_type IS TABLE OF employees.employee_id%TYPE 
  INDEX BY BINARY_INTEGER;  -- Type Associative Array
  employee_id_table  employee_id_table_type;
  CURSOR employees_cursor IS
    SELECT employee_id 
    FROM employees;
BEGIN

  OPEN employees_cursor;
  
  LOOP
    FETCH employees_cursor 
    BULK COLLECT INTO employee_id_table LIMIT vlimit;
    
    EXIT WHEN employee_id_table.COUNT = 0;
    
    DBMS_OUTPUT.PUT_LINE('Linhas recuperadas: ' || employee_id_table.COUNT);
    
    FORALL indice IN 1..employee_id_table.COUNT 
      
      UPDATE employees e
      SET    e.salary = e.salary * (1 + ppercentual / 100)
      WHERE  e.employee_id = employee_id_table(indice);  
    
  END LOOP;
  
  CLOSE employees_cursor;
  -- COMMIT;
  
END;

SELECT *
FROM employees;

--- Executando PRC_UPDATE_SALARY2 

exec PRC_UPDATE_SALARY2(10)

-- Consultando

SELECT *
FROM employees;

ROLLBACK;







```

<!-- TOC --><a name="section-22-sql-dynamic"></a>
# Section 22 - SQL Dynamic


<!-- TOC --><a name="1-execute-immediatesql"></a>
## 1 - EXECUTE IMMEDIATE.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 26 - SQL Dinâmico - Execute Immediate e variáveis Bind
--
-- Aula 1 - SQL Dinamico - EXECUTE IMMEDIATE

-- SQL Dinamico - EXECUTE IMMEDIATE

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_FETCH_EMPLOYEES_DYNAMIC
  (pmanager_id         IN employees.manager_id%TYPE DEFAULT NULL,
   pdepartment_id      IN employees.department_id%TYPE DEFAULT NULL)
AS
  vemployees_record  employees%ROWTYPE;
  vsql               VARCHAR2(600) := 'SELECT *
                                       FROM employees
                                       WHERE 1=1 ';
  TYPE  employees_table_type IS TABLE OF employees%ROWTYPE   -- Associative Array
  INDEX BY PLS_INTEGER;
  employees_table            employees_table_type;
  
BEGIN

  IF  pmanager_id IS NOT NULL THEN
      vsql := vsql || ' AND manager_id = ' || pmanager_id;
  END IF;
  
  IF  pdepartment_id IS NOT NULL THEN
      vsql := vsql || ' AND department_id = ' || pdepartment_id;
  END IF;
  
  DBMS_OUTPUT.PUT_LINE(vsql);
  
  EXECUTE IMMEDIATE vsql 
  BULK COLLECT INTO employees_table; 
  
  FOR i IN 1..employees_table.COUNT  LOOP
  
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' ||
                         employees_table(i).first_name || ' - ' ||
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).email || ' - ' ||
                         employees_table(i).manager_id || ' - ' ||
                         employees_table(i).department_id);
    
  END LOOP;
  
EXCEPTION
  WHEN OTHERS THEN 
       RAISE_APPLICATION_ERROR(-20001,'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando a procedure

exec PRC_FETCH_EMPLOYEES_DYNAMIC(pmanager_id => 103, pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_DYNAMIC(pmanager_id => 103)

exec PRC_FETCH_EMPLOYEES_DYNAMIC(pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_DYNAMIC
```

<!-- TOC --><a name="2-execute-immediate-with-bind-variablessql"></a>
## 2 - EXECUTE IMMEDIATE with BIND VARIABLES.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 26 - SQL Dinâmico - Execute Immediate e variáveis Bind
--
-- Aula 2 - SQL Dinamico com EXECUTE IMMEDIATE e variáveis Bind

-- SQL Dinamico - EXECUTE IMMEDIATE e variáveis Bind


SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_FETCH_EMPLOYEES_DYNAMIC_BIND
  (pmanager_id         IN employees.manager_id%TYPE DEFAULT NULL,
   pdepartment_id      IN employees.department_id%TYPE DEFAULT NULL)
AS
  vemployees_record  employees%ROWTYPE;
  vsql               VARCHAR2(600) := 'SELECT *
                                       FROM employees
                                       WHERE 1=1 ';
  TYPE  employees_table_type IS TABLE OF employees%ROWTYPE   -- Associative Array
  INDEX BY PLS_INTEGER;
  employees_table            employees_table_type;
  
BEGIN

  IF  pmanager_id IS NOT NULL THEN
      vsql := vsql || ' AND manager_id = :manager_id';
  END IF;
  
  IF  pdepartment_id IS NOT NULL THEN
      vsql := vsql || ' AND department_id = :department_id';
  END IF;
  
  DBMS_OUTPUT.PUT_LINE(vsql);
  
  CASE
    WHEN pmanager_id IS NOT NULL AND pdepartment_id IS NOT NULL THEN
         EXECUTE IMMEDIATE vsql BULK COLLECT INTO employees_table USING pmanager_id, pdepartment_id;
    WHEN pmanager_id IS NOT NULL AND pdepartment_id is NULL THEN
         EXECUTE IMMEDIATE vsql BULK COLLECT INTO employees_table USING pmanager_id;
    WHEN pmanager_id IS NULL AND pdepartment_id IS NOT NULL THEN
         EXECUTE IMMEDIATE vsql BULK COLLECT INTO employees_table USING pdepartment_id;
    ELSE
         EXECUTE IMMEDIATE vsql BULK COLLECT INTO employees_table;
  END CASE;    
  
  FOR i IN 1..employees_table.COUNT  LOOP
  
    DBMS_OUTPUT.PUT_LINE(employees_table(i).employee_id || ' - ' ||
                         employees_table(i).first_name || ' - ' ||
                         employees_table(i).last_name || ' - ' ||
                         employees_table(i).email || ' - ' ||
                         employees_table(i).manager_id || ' - ' ||
                         employees_table(i).department_id);
    
  END LOOP;
  
EXCEPTION
  WHEN OTHERS THEN 
       RAISE_APPLICATION_ERROR(-20001,'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando a procedure

exec PRC_FETCH_EMPLOYEES_DYNAMIC_BIND(pmanager_id => 103, pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_DYNAMIC_BIND(pmanager_id => 103)

exec PRC_FETCH_EMPLOYEES_DYNAMIC_BIND(pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_DYNAMIC_BIND;
```

<!-- TOC --><a name="invoking-subprogram-from-dynamic-sql-blocksql"></a>
## Invoking Subprogram from Dynamic SQL Block.sql
```sql
-- Subprogram that dynamic PL/SQL block invokes:
CREATE OR REPLACE PROCEDURE create_dept (
  deptid IN OUT NUMBER,
  dname  IN     VARCHAR2,
  mgrid  IN     NUMBER,
  locid  IN     NUMBER
) AUTHID DEFINER AS
BEGIN
  deptid := departments_seq.NEXTVAL;

  INSERT INTO departments (
    department_id,
    department_name,
    manager_id,
    location_id
  )
  VALUES (deptid, dname, mgrid, locid);
END;
/

DECLARE
  plsql_block VARCHAR2(500);
  new_deptid  NUMBER(4);
  new_dname   VARCHAR2(30) := 'Advertising';
  new_mgrid   NUMBER(6)    := 200;
  new_locid   NUMBER(4)    := 1700;
BEGIN
 -- Dynamic PL/SQL block invokes subprogram:
  plsql_block := 'BEGIN create_dept(:a, :b, :c, :d); END;';

 /* Specify bind variables in USING clause.
    Specify mode for first parameter.
    Modes of other parameters are correct by default. */

  EXECUTE IMMEDIATE plsql_block
    USING IN OUT new_deptid, new_dname, new_mgrid, new_locid;
    
  DBMS_OUTPUT.PUT_LINE('DEPT ID: ' || new_deptid);
END;
/

```

<!-- TOC --><a name="section-23-dbms_sql"></a>
# Section 23 - DBMS_SQL


<!-- TOC --><a name="1-dbms_sqlsql"></a>
## 1 - DBMS_SQL.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 27 - SQL Dinâmico -  DBMS_SQL

-- Aula 1 - SQL Dinamico - DBMS_SQL

-- SQL Dinamico - DBMS_SQL

-- Comando DML

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_UPDATE_SALARY_EMPLOYEE
  (pemployee_id        IN employees.employee_id%TYPE,
   ppercentual         IN NUMBER)
IS
  vcursor_id       INTEGER;
  vrows_processed  INTEGER;
BEGIN

  -- OPEN Cursor
  vcursor_id  := DBMS_SQL.OPEN_CURSOR;
  
  -- Parsing comando SQL
  DBMS_SQL.PARSE(vcursor_id, 'UPDATE employees
                              SET    salary = salary * (1 + (:gpercentual/100))
                              WHERE  employee_id = :gemployee_id', DBMS_SQL.NATIVE);

  -- Binding Variáveis
  DBMS_SQL.BIND_VARIABLE(vcursor_id, ':gpercentual', ppercentual);
  DBMS_SQL.BIND_VARIABLE(vcursor_id, ':gemployee_id', pemployee_id);
  
  -- Executando o Cursor
  vrows_processed := DBMS_SQL.EXECUTE(vcursor_id);
  
  -- CLOSE Cursor
  DBMS_SQL.CLOSE_CURSOR(vcursor_id);
  
  --COMMIT;
  
EXCEPTION
   WHEN OTHERS THEN 
       RAISE_APPLICATION_ERROR(-20001,'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando a procedure

SELECT *
FROM   employees;

exec PRC_UPDATE_SALARY_EMPLOYEE(pemployee_id => 109, ppercentual => 10)

SELECT *
FROM   employees;

ROLLBACK;		

-- SQL Dinamico - DBMS_SQL

-- Comando SELECT

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE

  vcursor_id   INTEGER;
  vrowcount    NUMBER;
  vfirst_name  VARCHAR2(30);
  vlast_name   VARCHAR2(30);

BEGIN

  vcursor_id  :=  DBMS_SQL.OPEN_CURSOR;

  DBMS_SQL.PARSE(vcursor_id,'SELECT first_name,last_name FROM employees', DBMS_SQL.NATIVE);

  DBMS_SQL.DEFINE_COLUMN(vcursor_id,1,vfirst_name,30);

  DBMS_SQL.DEFINE_COLUMN(vcursor_id,2,vlast_name,30);

  vrowcount := DBMS_SQL.EXECUTE_AND_FETCH(vcursor_id);

  LOOP

    EXIT WHEN DBMS_SQL.FETCH_ROWS(vcursor_id) = 0;

    DBMS_SQL.COLUMN_VALUE(vcursor_id,1,vfirst_name);

    DBMS_SQL.COLUMN_VALUE(vcursor_id,2,vlast_name);

    DBMS_OUTPUT.PUT_LINE(vlast_name||', '||vfirst_name);

   END LOOP;

   DBMS_SQL.CLOSE_CURSOR(vcursor_id);

END;
	  

```

<!-- TOC --><a name="section-24-cursor-com-sql-dynamic"></a>
# Section 24 - Cursor com SQL Dynamic


<!-- TOC --><a name="1-cursor-explicit-com-sql-dynamicsql"></a>
## 1 - Cursor Explicit com SQL Dynamic.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 28 - Cursor Explícito com SQL Dinâmico
--
-- Aula 1 - Cursor Explícito com SQL Dinâmico

-- SQL Dinamico com Cursor

SET SERVEROUTPUT ON
SET VERIFY OFF
CREATE OR REPLACE PROCEDURE PRC_FETCH_EMPLOYEES_CURSOR_DYNAMIC
  (pmanager_id         IN employees.manager_id%TYPE DEFAULT NULL,
   pdepartment_id      IN employees.department_id%TYPE DEFAULT NULL)
AS
  TYPE employees_cursor_type IS REF CURSOR;
  employees_cursor           employees_cursor_type;
  vemployees_record          employees%ROWTYPE;
  vsql                       VARCHAR2(600) := 'SELECT *
                                               FROM employees
                                               WHERE 1=1 ';
BEGIN
  IF  pmanager_id IS NOT NULL THEN
      vsql := vsql || ' AND manager_id = :manager_id';
  END IF;
  IF  pdepartment_id IS NOT NULL THEN
      vsql := vsql || ' AND department_id = :department_id';
  END IF;
  
  DBMS_OUTPUT.PUT_LINE(vsql);
  
  CASE
    WHEN pmanager_id IS NOT NULL AND pdepartment_id IS NOT NULL THEN
         OPEN employees_cursor FOR vsql USING pmanager_id, pdepartment_id;
    WHEN pmanager_id IS NOT NULL AND pdepartment_id is NULL THEN
         OPEN employees_cursor FOR vsql USING pmanager_id;
    WHEN pmanager_id IS NULL AND pdepartment_id IS NOT NULL THEN
         OPEN employees_cursor FOR vsql USING pdepartment_id;
    ELSE
         OPEN employees_cursor FOR vsql;
  END CASE;  
  
  LOOP
    FETCH  employees_cursor
    INTO   vemployees_record;
    
    EXIT WHEN employees_cursor%NOTFOUND;
    
    DBMS_OUTPUT.PUT_LINE(vemployees_record.employee_id || ' - ' ||
                         vemployees_record.first_name || ' - ' ||
                         vemployees_record.last_name || ' - ' ||
                         vemployees_record.email || ' - ' ||
                         vemployees_record.manager_id || ' - ' ||
                         vemployees_record.department_id);
    
  END LOOP;
  
  CLOSE employees_cursor;
  
EXCEPTION
   WHEN OTHERS THEN 
       RAISE_APPLICATION_ERROR(-20001,'Erro Oracle ' || SQLCODE || SQLERRM);
END;

-- Executando a procedure

exec PRC_FETCH_EMPLOYEES_CURSOR_DYNAMIC(pmanager_id => 103, pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_CURSOR_DYNAMIC(pmanager_id => 103)

exec PRC_FETCH_EMPLOYEES_CURSOR_DYNAMIC(pdepartment_id => 60)

exec PRC_FETCH_EMPLOYEES_CURSOR_DYNAMIC;
```

<!-- TOC --><a name="section-25-dbms_scheduler"></a>
# Section 25 - DBMS_SCHEDULER


<!-- TOC --><a name="1-creating-one-programasql"></a>
## 1 - Creating one Programa.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 29 - Package DBMS_SCHEDULLER
--
-- Aula 2 - Criando um Programa

-- Criando e Habilitando um Programa

-- Conectar como SYS

grant CREATE JOB to hr;

-- Conectar como sales

DROP TABLE AGENDA;

CREATE TABLE AGENDA
(agenda_id    NUMBER,
 agenda_data  DATE);
 
DROP SEQUENCE AGENDA_SEQ;
 
CREATE SEQUENCE AGENDA_SEQ
START WITH 1
INCREMENT BY 1
NOCACHE
NOMAXVALUE
NOCYCLE;

CREATE OR REPLACE PROCEDURE PRC_INSERE_DATA_AGENDA
IS
BEGIN
  INSERT INTO hr.agenda
  VALUES (agenda_seq.NEXTVAL, sysdate);
  COMMIT;
END;

-- Criando e Habilitado um Programa

BEGIN
    DBMS_SCHEDULER.create_program(
        program_name => 'HR.PRC_INSERE_AGENDA',
        program_action => 'HR.PRC_INSERE_DATA_AGENDA',
        program_type => 'STORED_PROCEDURE',
        number_of_arguments => 0,
        comments => 'Insere dados na agenda',
        enabled => TRUE);
/*
    DBMS_SCHEDULER.ENABLE(name=>'HR.PRC_INSERE_AGENDA');    
*/
END;

-- Removendo um Programa

BEGIN
    DBMS_SCHEDULER.drop_program(
        program_name => 'HR.PRC_INSERE_AGENDA',
        force => TRUE);
END;

-- Criando e Habilitado um Programa

BEGIN
    DBMS_SCHEDULER.create_program(
        program_name => 'HR.PRC_INSERE_AGENDA',
        program_action => 'HR.PRC_INSERE_DATA_AGENDA',
        program_type => 'STORED_PROCEDURE',
        number_of_arguments => 0,
        comments => 'Insere dados na agenda',
        enabled => TRUE);

    -- DBMS_SCHEDULER.ENABLE(name=>'HR.PRC_INSERE_AGENDA');    

END;
 

```

<!-- TOC --><a name="2-creating-one-agendasql"></a>
## 2 - Creating one Agenda.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 29 - Package DBMS_SCHEDULLER
--
-- Aula 3 - Criando uma Agenda

-- Criando uma Agenda

-- Conectar como SYS

grant CREATE JOB to hr;
 
-- Criando um Schedule (a cada 10 segundos)
 
BEGIN
    DBMS_SCHEDULER.CREATE_SCHEDULE (
        schedule_name  => 'SCH_A_CADA_10_SEGUNDOS',
        start_date     => SYSTIMESTAMP,
        --start_date => TO_TIMESTAMP_TZ('2020-03-17 15:17:36.000000000 AMERICA/SAO_PAULO','YYYY-MM-DD HH24:MI:SS.FF TZR'),
        repeat_interval  => 'FREQ=SECONDLY;INTERVAL=10',
        end_date => TO_TIMESTAMP_TZ('2020-07-23 23:00:00.000000000 AMERICA/SAO_PAULO','YYYY-MM-DD HH24:MI:SS.FF TZR'),
        comments => 'A cada 10 segundos'
        );
END;
 
--Removendo um Schedule 
 
BEGIN
    DBMS_SCHEDULER.DROP_SCHEDULE (
        schedule_name  => 'SCH_A_CADA_10_SEGUNDOS',
        force    => FALSE
        );
END;

-- Criando um Schedule (a cada 10 segundos)
 
BEGIN
    DBMS_SCHEDULER.CREATE_SCHEDULE (
        schedule_name  => 'SCH_A_CADA_10_SEGUNDOS',
        start_date     => SYSTIMESTAMP,
        -- start_date => TO_TIMESTAMP_TZ('2020-03-17 15:17:36.000000000 AMERICA/SAO_PAULO','YYYY-MM-DD HH24:MI:SS.FF TZR'),
        repeat_interval  => 'FREQ=SECONDLY;INTERVAL=10',
        end_date => TO_TIMESTAMP_TZ('2020-07-23 23:00:00.000000000 AMERICA/SAO_PAULO','YYYY-MM-DD HH24:MI:SS.FF TZR'),
        comments => 'A cada 10 segundos'
        );
END;




```

<!-- TOC --><a name="3-creating-one-jobsql"></a>
## 3 - Creating one Job.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 29 - Package DBMS_SCHEDULLER
--
-- Aula 4 - Criando um Job

-- Criando um Job

-- Conectar como SYS

grant CREATE JOB to hr;

BEGIN
    DBMS_SCHEDULER.CREATE_JOB (
            job_name => '"HR"."JOB_INSERE_DATA_AGENDA"',
            program_name => '"HR"."PRC_INSERE_AGENDA"',
            schedule_name => '"HR"."SCH_A_CADA_10_SEGUNDOS"',
            enabled => TRUE,
            auto_drop => FALSE,
            comments => 'Job Insere Data na Agenda',             
            job_style => 'REGULAR');
/*
    DBMS_SCHEDULER.enable(
             name => '"HR"."JOB_INSERE_DATA_AGENDA"');
*/
END;

-- Consultando a tabela AGENDA

SELECT agenda_id, TO_CHAR(agenda_data,'dd/mm/yyyy hh24:mi:ss') AGENDA_DATA
FROM   agenda
ORDER BY agenda_id;

-- Conectar como SYS

-- Remover o job

BEGIN
	DBMS_SCHEDULER.DROP_JOB (
	     job_name => '"HR"."JOB_INSERE_DATA_AGENDA"',
	     force => TRUE);
END;


```

<!-- TOC --><a name="section-26-utl_file"></a>
# Section 26 - UTL_FILE


<!-- TOC --><a name="1-utl_filesql"></a>
## 1 - UTL_FILE.sql
```sql
/* Create a directory reference */
CREATE OR REPLACE DIRECTORY FILES AS 'C:\oracle21c\files';
/

/* === Writing a file ===*/
DECLARE
  vfFile UTL_FILE.FILE_TYPE;

  CURSOR vcEmployees IS
    SELECT employee_id, first_name, last_name, job_id, salary
      FROM employees;
BEGIN
  -- UTL_FILE.FOPEN(directory, filename, type, size)
  vfFile := UTL_FILE.FOPEN('FILES', 'employees.txt', 'w', 32767);

  FOR vrEmployees IN vcEmployees LOOP
    UTL_FILE.PUT_LINE(vfFile,
                      vrEmployees.employee_id || ';' ||
                      vremployees.first_name  || ';' ||
                      vrEmployees.last_name   || ';' || 
                      vrEmployees.job_id      || ';' ||
                      vrEmployees.salary);
  END LOOP;

  UTL_FILE.FCLOSE(vfFile);

EXCEPTION
  WHEN UTL_FILE.INVALID_PATH THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Invalid path.');
  WHEN UTL_FILE.INVALID_OPERATION THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Invalid operation.');
  WHEN UTL_FILE.WRITE_ERROR THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Error writing file.');
  WHEN UTL_FILE.INVALID_MODE THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Invalid access mode.');
  WHEN OTHERS THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Error:' || SQLCODE || SQLERRM);
END;
/

/* === Reading a file ===*/
DECLARE
  vfFile     UTL_FILE.FILE_TYPE;
  vsRegistro VARCHAR2(400);
BEGIN
  vfFile := UTL_FILE.FOPEN('FILES', 'employees.txt', 'r', 32767);
  LOOP
    UTL_FILE.GET_LINE(vfFile, vsRegistro);
    DBMS_OUTPUT.PUT_LINE(vsRegistro);
  END LOOP;

EXCEPTION
  WHEN NO_DATA_FOUND THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('File successfully read.');
  WHEN UTL_FILE.INVALID_PATH THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Invalid path.');
  WHEN OTHERS THEN
    UTL_FILE.FCLOSE(vfFile);
    DBMS_OUTPUT.PUT_LINE('Error:' || SQLCODE || SQLERRM);
  
END;

```

<!-- TOC --><a name="using-a-package-utl_file-to-ler-e-to-record-filessql"></a>
## Using a Package UTL_FILE to ler e to record files.sql
```sql
--
-- Oracle PL/SQL Avançado 
--
-- Seção 30 - Package UTL_FILE
--
-- Aula 1 - Package UTL_FILE

-- Package Package UTL_FILE

-- Criar o diretorio 'C:\ARQUIVOS' no Windows

-- Conectar como SYS

CREATE OR REPLACE DIRECTORY ARQUIVOS AS 'C:\ARQUIVOS';

GRANT READ, WRITE ON DIRECTORY ARQUIVOS TO hr;

-- Gravando um arquivo Texto

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  vfile  UTL_FILE.FILE_TYPE;
  CURSOR employees_c IS
  SELECT employee_id, first_name, last_name, job_id, salary
  FROM   employees;
BEGIN
  vfile := UTL_FILE.FOPEN('ARQUIVOS', 'employees.txt','w',32767);
  FOR  employees_r IN employees_c LOOP
    UTL_FILE.PUT_LINE(vfile, employees_r.employee_id || ';' || 
                             employees_r.first_name || ';' || 
                             employees_r.last_name || ';' ||
                             employees_r.job_id || ';' || 
                             employees_r.salary);
  END LOOP;
  UTL_FILE.FCLOSE(vfile);
  DBMS_OUTPUT.PUT_LINE('Arquivo Texto employees.txt gerado com sucesso');
EXCEPTION
  WHEN UTL_FILE.INVALID_PATH THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Diretório Inválido');
  WHEN UTL_FILE.INVALID_OPERATION THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Operação invalida no arquivo');
  WHEN UTL_FILE.WRITE_ERROR THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Erro de gravação no arquivo');     
  WHEN UTL_FILE.INVALID_MODE THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Modo de acesso inválido');
  WHEN OTHERS THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Erro Oracle:' || SQLCODE || SQLERRM);
END;

-- Lendo um arquivo Texto

SET SERVEROUTPUT ON
SET VERIFY OFF
DECLARE
  vfile  UTL_FILE.FILE_TYPE;
  vregistro  VARCHAR2(400);
BEGIN
  vfile := UTL_FILE.FOPEN('ARQUIVOS', 'employees.txt','r',32767);
  LOOP  
    UTL_FILE.GET_LINE(vfile, vregistro);
    DBMS_OUTPUT.PUT_LINE(vregistro);
  END LOOP;

EXCEPTION
  WHEN NO_DATA_FOUND THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Arquivo Texto employees.txt lido com sucesso');
  WHEN UTL_FILE.INVALID_PATH THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Diretório Inválido');
  WHEN OTHERS THEN
      UTL_FILE.FCLOSE(vfile);
      DBMS_OUTPUT.PUT_LINE('Erro Oracle:' || SQLCODE || SQLERRM);
END;

```

<!-- TOC --><a name="section-27-dbms_flashback"></a>
# Section 27 - DBMS_FLASHBACK


<!-- TOC --><a name="flashback-querysql"></a>
## FLASHBACK query.sql
```sql
-- Query the table
SELECT * FROM employees;

-- Causing an error
UPDATE employees e SET e.salary = e.salary * 2;
COMMIT;

DECLARE
  CURSOR vcEmployees IS
    SELECT *
      FROM employees AS OF TIMESTAMP(systimestamp - INTERVAL '30' minute);

  vrEmployees employees%ROWTYPE;
BEGIN
  OPEN vcEmployees;

  LOOP
    FETCH vcEmployees
      INTO vrEmployees;
    EXIT WHEN vcEmployees%NOTFOUND;
  
    UPDATE employees e
       SET e.salary = vrEmployees.salary
     WHERE e.employee_id = vrEmployees.employee_id;
  END LOOP;
  CLOSE vcEmployees;
  COMMIT;
END;
/

-- undo_retention = 900s 
SELECT NAME, VALUE FROM v$parameter WHERE NAME LIKE '%undo%';


```


