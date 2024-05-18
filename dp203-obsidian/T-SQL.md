T-SQL (Transact-SQL) is the dialect of SQL used by Microsoft SQL Server. Let's explore how to create tables in T-SQL.

### Creating a Basic Table
### Adding Constraints
### Creating a Table from an Existing Table

### Numeric Data Types

1. **INT**: 4-byte integer.
2. **BIGINT**: 8-byte integer.
3. **SMALLINT**: 2-byte integer.
4. **TINYINT**: 1-byte integer.
5. **DECIMAL(p, s)**: Fixed-point decimal number, where p is the total number of digits and s is the number of digits to the right of the decimal point.
6. **NUMERIC(p, s)**: Similar to DECIMAL, with fixed precision.
7. **FLOAT**: Double-precision floating-point number.

### Text Data Types

1. **CHAR(n)**: Fixed-length string of size n.
2. **VARCHAR(n)**: Variable-length string with a maximum size of n.
3. **TEXT**: Variable-length text, stored out of line.

### Date and Time Data Types

1. **DATE**: Date (year, month, day).
2. **TIME**: Time of day (hours, minutes, seconds, fractions of a second).
3. **DATETIME**: Date and time (year, month, day, hours, minutes, seconds, fractions of a second).
4. **DATETIME2**: Date and time with higher precision.
5. **SMALLDATETIME**: Date and time with less precision than DATETIME.

### Binary Data Types

1. **BINARY(n)**: Fixed-length binary data of size n.
2. **VARBINARY(n)**: Variable-length binary data with a maximum size of n.
3. **IMAGE**: Variable-length binary data, stored out of line.

### Other Data Types

1. **BIT**: Boolean value (0 or 1).
2. **UNIQUEIDENTIFIER**: Globally unique identifier (GUID).
3. **XML**: XML data.
4. **CURSOR**: Reference to a result set (typically used in stored procedures).
5. **GEOMETRY**: Geometric data (used in spatial applications).